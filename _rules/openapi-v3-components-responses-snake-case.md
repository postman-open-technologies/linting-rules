---
openapi-v3-components-responses-snake-case:
  description: Ensuring that all components responses are using snake case for the name.
  message: The component responses name needs to be snakeCase.
  given: $.components.responses
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
...
openapi-v3-components-responses-snake-case:
  description: Ensuring that all components responses are using snake case for the name.
  message: The component responses name needs to be snakeCase.
  given: $.components.responses
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
