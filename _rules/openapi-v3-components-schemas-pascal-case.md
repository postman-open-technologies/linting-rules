---
openapi-v3-components-schemas-pascal-case:
  description: Ensuring that all components schemas are using pascal case for the name.
  message: The component schemas name needs to be pascalCase.
  given: $.components.schemas
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
...
openapi-v3-components-schemas-pascal-case:
  description: Ensuring that all components schemas are using pascal case for the name.
  message: The component schemas name needs to be pascalCase.
  given: $.components.schemas
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
