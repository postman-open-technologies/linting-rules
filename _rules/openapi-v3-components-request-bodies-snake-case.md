---
openapi-v3-components-request-bodies-snake-case:
  description: >-
    Ensuring that all components request bodies are using snake case for the
    key.
  message: The component request bodies key needs to be snakeCase.
  given: $.components.requestBodies
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
...
openapi-v3-components-request-bodies-snake-case:
  description: >-
    Ensuring that all components request bodies are using snake case for the
    key.
  message: The component request bodies key needs to be snakeCase.
  given: $.components.requestBodies
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
