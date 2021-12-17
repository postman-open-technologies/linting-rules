---
openapi-v3-info-license-name:
  description: Ensures that all OpenAPIs have a information object license name.
  message: The info object should have a license name.
  given: $.info.license
  severity: error
  then:
    field: name
    function: truthy
...
openapi-v3-info-license-name:
  description: Ensures that all OpenAPIs have a information object license name.
  message: The info object should have a license name.
  given: $.info.license
  severity: error
  then:
    field: name
    function: truthy
