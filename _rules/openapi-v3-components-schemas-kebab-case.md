---
openapi-v3-components-schemas-kebab-case:
  description: Ensuring that all components schemas are using kebab case for the name.
  message: The component schemas name needs to be kebabCase.
  given: $.components.schemas
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: kebab
...
openapi-v3-components-schemas-kebab-case:
  description: Ensuring that all components schemas are using kebab case for the name.
  message: The component schemas name needs to be kebabCase.
  given: $.components.schemas
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: kebab
