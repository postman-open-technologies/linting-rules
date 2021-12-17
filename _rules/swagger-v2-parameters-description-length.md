---
swagger-v2-parameters-description-length:
  description: Ensures that each of parameter description isn't too long.
  message: Your parameter descriptions can't be more than 500 characters.
  given: $.paths.*.*.parameters[?(@.in=='query')].description
  then:
    field: summary
    function: length
    functionOptions:
      max: 500
...
swagger-v2-parameters-description-length:
  description: Ensures that each of parameter description isn't too long.
  message: Your parameter descriptions can't be more than 500 characters.
  given: $.paths.*.*.parameters[?(@.in=='query')].description
  then:
    field: summary
    function: length
    functionOptions:
      max: 500
