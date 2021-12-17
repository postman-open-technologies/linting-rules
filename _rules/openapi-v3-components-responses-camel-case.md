---
openapi-v3-components-responses-camel-case:
  description: Ensuring that all components responses are using camel case for the name.
  message: The component responses name needs to be camelCase.
  given: $.components.responses
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
...
openapi-v3-components-responses-camel-case:
  description: Ensuring that all components responses are using camel case for the name.
  message: The component responses name needs to be camelCase.
  given: $.components.responses
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
