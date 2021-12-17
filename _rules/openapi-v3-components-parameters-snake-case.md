---
openapi-v3-components-parameters-snake-case:
  description: Ensuring that all components parameters are using snake case for the name.
  message: The component parameters name needs to be snakeCase.
  given: >-
    $.components.parameters..[?(@.in==='query' || @.in==='path' ||
    @.in==='cookie')]
  severity: warn
  then:
    field: name
    function: casing
    functionOptions:
      type: snake
...
openapi-v3-components-parameters-snake-case:
  description: Ensuring that all components parameters are using snake case for the name.
  message: The component parameters name needs to be snakeCase.
  given: >-
    $.components.parameters..[?(@.in==='query' || @.in==='path' ||
    @.in==='cookie')]
  severity: warn
  then:
    field: name
    function: casing
    functionOptions:
      type: snake
