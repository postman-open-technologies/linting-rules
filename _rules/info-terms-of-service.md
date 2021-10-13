---
info-terms-of-service:
  description: The API must have a terms of service applied.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: termsOfService
      function: truthy  
  x-status: validated
  x-tags:
    - Terms of Service
    - Legal
...
info-terms-of-service:
  description: The API must have a terms of service applied.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: termsOfService
      function: truthy  
  x-status: validated
  x-tags:
    - Terms of Service
    - Legal