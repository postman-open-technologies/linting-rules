---
openapi-v3-components-schemas-snake-case:
  description: Ensuring that all components schemas are using snake case for the name.
  message: The component schemas name needs to be snakeCase.
  given: $.components.schemas
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
...
openapi-v3-components-schemas-snake-case:
  description: Ensuring that all components schemas are using snake case for the name.
  message: The component schemas name needs to be snakeCase.
  given: $.components.schemas
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
