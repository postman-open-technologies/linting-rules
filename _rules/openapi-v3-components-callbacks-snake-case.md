---
openapi-v3-components-callbacks-snake-case:
  description: Ensuring that all components callbacks are using snake case for the key.
  message: The component callback key needs to be snakeCase.
  given: $.components.callbacks
  severity: error
  formats:
    - oas3
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
...
openapi-v3-components-callbacks-snake-case:
  description: Ensuring that all components callbacks are using snake case for the key.
  message: The component callback key needs to be snakeCase.
  given: $.components.callbacks
  severity: error
  formats:
    - oas3
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
