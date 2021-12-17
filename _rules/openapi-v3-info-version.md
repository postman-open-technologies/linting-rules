---
openapi-v3-info-version:
  description: Ensures that all OpenAPIs have a information object version.
  message: The info object should have a version.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    field: version
    function: truthy
...
openapi-v3-info-version:
  description: Ensures that all OpenAPIs have a information object version.
  message: The info object should have a version.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    field: version
    function: truthy
