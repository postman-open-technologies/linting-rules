---
swagger-v2-info-version:
  description: Ensures that all Swaggers have a information object version.
  message: The info object should have a version.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    field: version
    function: truthy
...
swagger-v2-info-version:
  description: Ensures that all Swaggers have a information object version.
  message: The info object should have a version.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    field: version
    function: truthy
