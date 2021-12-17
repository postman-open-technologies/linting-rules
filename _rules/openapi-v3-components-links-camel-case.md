---
openapi-v3-components-links-camel-case:
  description: Ensuring that all components links are using camel case for the key.
  message: The component links key needs to be camelCase.
  given: $.components.links
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
...
openapi-v3-components-links-camel-case:
  description: Ensuring that all components links are using camel case for the key.
  message: The component links key needs to be camelCase.
  given: $.components.links
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
