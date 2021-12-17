---
swagger-v2-parameters-name-pascal-case:
  description: Ensures that that all parameter names are pascal case.
  message: Your parameter names should all be pascal case.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    field: name
    function: casing
    functionOptions:
      type: pascal
...
swagger-v2-parameters-name-pascal-case:
  description: Ensures that that all parameter names are pascal case.
  message: Your parameter names should all be pascal case.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    field: name
    function: casing
    functionOptions:
      type: pascal
