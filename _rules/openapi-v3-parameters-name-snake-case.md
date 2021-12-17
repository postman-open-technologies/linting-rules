---
openapi-v3-parameters-name-snake-case:
  description: Ensures that that all parameter names are snake case.
  message: Your parameter names should all be snake case.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    field: name
    function: casing
    functionOptions:
      type: snake
...
openapi-v3-parameters-name-snake-case:
  description: Ensures that that all parameter names are snake case.
  message: Your parameter names should all be snake case.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    field: name
    function: casing
    functionOptions:
      type: snake
