---
swagger-v2-parameters-name-length:
  description: Ensures that that parameter names aren't too long.
  message: Your parameter names should not be longer than 25 characters.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    field: summary
    function: length
    functionOptions:
      max: 25
...
swagger-v2-parameters-name-length:
  description: Ensures that that parameter names aren't too long.
  message: Your parameter names should not be longer than 25 characters.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    field: summary
    function: length
    functionOptions:
      max: 25
