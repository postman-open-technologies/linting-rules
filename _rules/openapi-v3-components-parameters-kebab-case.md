---
openapi-v3-components-parameters-kebab-case:
  description: Ensuring that all components parameters are using kebab case for the name.
  message: The component parameters name needs to be kebabCase.
  given: >-
    $.components.parameters..[?(@.in==='query' || @.in==='path' ||
    @.in==='cookie')]
  severity: warn
  then:
    field: name
    function: casing
    functionOptions:
      type: kebab
...
openapi-v3-components-parameters-kebab-case:
  description: Ensuring that all components parameters are using kebab case for the name.
  message: The component parameters name needs to be kebabCase.
  given: >-
    $.components.parameters..[?(@.in==='query' || @.in==='path' ||
    @.in==='cookie')]
  severity: warn
  then:
    field: name
    function: casing
    functionOptions:
      type: kebab
