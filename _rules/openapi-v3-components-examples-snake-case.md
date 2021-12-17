---
openapi-v3-components-examples-snake-case:
  description: Ensuring that all components example are using snake case for the key.
  message: The component example key needs to be snakeCase.
  given: $.components.examples
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
...
openapi-v3-components-examples-snake-case:
  description: Ensuring that all components example are using snake case for the key.
  message: The component example key needs to be snakeCase.
  given: $.components.examples
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
