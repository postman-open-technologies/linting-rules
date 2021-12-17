---
openapi-v3-components-callbacks-camel-case:
  description: Ensuring that all components callbacks are using camel case for the key.
  message: The component callback key needs to be camelCase.
  given: $.components.callbacks
  severity: error
  formats:
    - oas3
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
...
openapi-v3-components-callbacks-camel-case:
  description: Ensuring that all components callbacks are using camel case for the key.
  message: The component callback key needs to be camelCase.
  given: $.components.callbacks
  severity: error
  formats:
    - oas3
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
