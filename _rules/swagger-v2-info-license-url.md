---
swagger-v2-info-license-url:
  description: Ensures that all Swaggers have a information object license url.
  message: The info object should have a license url.
  given: $.info.license
  severity: error
  then:
    field: url
    function: truthy
...
swagger-v2-info-license-url:
  description: Ensures that all Swaggers have a information object license url.
  message: The info object should have a license url.
  given: $.info.license
  severity: error
  then:
    field: url
    function: truthy
