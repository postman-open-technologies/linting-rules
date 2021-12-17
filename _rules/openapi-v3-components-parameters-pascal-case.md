---
openapi-v3-components-parameters-pascal-case:
  description: Ensuring that all components parameters are using pascal case for the name.
  message: The component parameters name needs to be pascalCase.
  given: >-
    $.components.parameters..[?(@.in==='query' || @.in==='path' ||
    @.in==='cookie')]
  severity: warn
  then:
    field: name
    function: casing
    functionOptions:
      type: pascal
...
openapi-v3-components-parameters-pascal-case:
  description: Ensuring that all components parameters are using pascal case for the name.
  message: The component parameters name needs to be pascalCase.
  given: >-
    $.components.parameters..[?(@.in==='query' || @.in==='path' ||
    @.in==='cookie')]
  severity: warn
  then:
    field: name
    function: casing
    functionOptions:
      type: pascal
