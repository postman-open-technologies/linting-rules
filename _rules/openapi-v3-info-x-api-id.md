---
openapi-v3-info-x-api-id:
  description: Ensures that all OpenAPIs have a information object API ID extension.
  message: The info object should have an API ID extension.
  given: $.info
  severity: error
  recommended: true
  type: style
  then:
    field: x-api-id
    function: truthy
...
openapi-v3-info-x-api-id:
  description: Ensures that all OpenAPIs have a information object API ID extension.
  message: The info object should have an API ID extension.
  given: $.info
  severity: error
  recommended: true
  type: style
  then:
    field: x-api-id
    function: truthy
