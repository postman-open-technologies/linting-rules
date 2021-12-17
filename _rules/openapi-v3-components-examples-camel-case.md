---
openapi-v3-components-examples-camel-case:
  description: Ensuring that all components example are using camel case for the key.
  message: The component example key needs to be camelCase.
  given: $.components.examples
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
...
openapi-v3-components-examples-camel-case:
  description: Ensuring that all components example are using camel case for the key.
  message: The component example key needs to be camelCase.
  given: $.components.examples
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
