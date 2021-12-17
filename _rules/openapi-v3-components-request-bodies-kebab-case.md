---
openapi-v3-components-request-bodies-kebab-case:
  description: >-
    Ensuring that all components request bodies are using kebab case for the
    key.
  message: The component request bodies key needs to be kebabCase.
  given: $.components.requestBodies
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: kebab
...
openapi-v3-components-request-bodies-kebab-case:
  description: >-
    Ensuring that all components request bodies are using kebab case for the
    key.
  message: The component request bodies key needs to be kebabCase.
  given: $.components.requestBodies
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: kebab
