---
openapi-v3-components-request-bodies-pascal-case:
  description: >-
    Ensuring that all components request bodies are using pascal case for the
    key.
  message: The component request bodies key needs to be pascalCase.
  given: $.components.requestBodies
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
...
openapi-v3-components-request-bodies-pascal-case:
  description: >-
    Ensuring that all components request bodies are using pascal case for the
    key.
  message: The component request bodies key needs to be pascalCase.
  given: $.components.requestBodies
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
