---
openapi-v3-info-terms-of-service:
  description: Ensures that all OpenAPIs have a information object terms of service.
  message: The info object should have a terms of service.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    field: termsOfService
    function: truthy
...
openapi-v3-info-terms-of-service:
  description: Ensures that all OpenAPIs have a information object terms of service.
  message: The info object should have a terms of service.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    field: termsOfService
    function: truthy
