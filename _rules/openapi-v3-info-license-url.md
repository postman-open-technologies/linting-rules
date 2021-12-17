---
openapi-v3-info-license-url:
  description: Ensures that all OpenAPIs have a information object license url.
  message: The info object should have a license url.
  given: $.info.license
  severity: error
  then:
    field: url
    function: truthy
...
openapi-v3-info-license-url:
  description: Ensures that all OpenAPIs have a information object license url.
  message: The info object should have a license url.
  given: $.info.license
  severity: error
  then:
    field: url
    function: truthy
