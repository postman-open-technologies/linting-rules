---
openapi-v3-components-links-snake-case:
  description: Ensuring that all components links are using snake case for the key.
  message: The component links key needs to be snakeCase.
  given: $.components.links
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
...
openapi-v3-components-links-snake-case:
  description: Ensuring that all components links are using snake case for the key.
  message: The component links key needs to be snakeCase.
  given: $.components.links
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
