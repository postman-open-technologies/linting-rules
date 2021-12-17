---
swagger-v2-info-terms-of-service:
  description: Ensures that all Swaggers have a information object terms of service.
  message: The info object should have a terms of service.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    field: termsOfService
    function: truthy
...
swagger-v2-info-terms-of-service:
  description: Ensures that all Swaggers have a information object terms of service.
  message: The info object should have a terms of service.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    field: termsOfService
    function: truthy
