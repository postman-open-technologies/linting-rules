---
openapi-v3-info-license:
  description: Ensures that all OpenAPIs have a information object license.
  message: The info object should have a license.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    field: license
    function: truthy
...
openapi-v3-info-license:
  description: Ensures that all OpenAPIs have a information object license.
  message: The info object should have a license.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    field: license
    function: truthy
