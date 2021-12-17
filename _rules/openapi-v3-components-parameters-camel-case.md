---
openapi-v3-components-parameters-camel-case:
  description: Ensuring that all components parameters are using camel case for the name.
  message: The component parameters name needs to be camelCase.
  given: >-
    $.components.parameters..[?(@.in==='query' || @.in==='path' ||
    @.in==='cookie')]
  severity: warn
  then:
    field: name
    function: casing
    functionOptions:
      type: camel
...
openapi-v3-components-parameters-camel-case:
  description: Ensuring that all components parameters are using camel case for the name.
  message: The component parameters name needs to be camelCase.
  given: >-
    $.components.parameters..[?(@.in==='query' || @.in==='path' ||
    @.in==='cookie')]
  severity: warn
  then:
    field: name
    function: casing
    functionOptions:
      type: camel
