---
openapi-v3-components-schemas-camel-case:
  description: Ensuring that all components schemas are using camel case for the name.
  message: The component schemas name needs to be camelCase.
  given: $.components.schemas
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
...
openapi-v3-components-schemas-camel-case:
  description: Ensuring that all components schemas are using camel case for the name.
  message: The component schemas name needs to be camelCase.
  given: $.components.schemas
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
