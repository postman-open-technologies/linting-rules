---
swagger-v2-info-license:
  description: Ensures that all Swaggers have a information object license.
  message: The info object should have a license.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    field: license
    function: truthy
...
swagger-v2-info-license:
  description: Ensures that all Swaggers have a information object license.
  message: The info object should have a license.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    field: license
    function: truthy
