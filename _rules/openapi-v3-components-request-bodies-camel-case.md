---
openapi-v3-components-request-bodies-camel-case:
  description: >-
    Ensuring that all components request bodies are using camel case for the
    key.
  message: The component request bodies key needs to be camelCase.
  given: $.components.requestBodies
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
...
openapi-v3-components-request-bodies-camel-case:
  description: >-
    Ensuring that all components request bodies are using camel case for the
    key.
  message: The component request bodies key needs to be camelCase.
  given: $.components.requestBodies
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
