---
openapi-v3-info-summary:
  description: Ensures that all OpenAPIs have a information object summary.
  message: The info object should have a summary.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    field: summary
    function: truthy
...
openapi-v3-info-summary:
  description: Ensures that all OpenAPIs have a information object summary.
  message: The info object should have a summary.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    field: summary
    function: truthy
