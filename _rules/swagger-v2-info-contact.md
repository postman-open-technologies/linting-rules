---
swagger-v2-info-contact:
  description: Ensures that all APIs have contact information.
  message: API must have a contact information available.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    field: contact
    function: truthy
...
swagger-v2-info-contact:
  description: Ensures that all APIs have contact information.
  message: API must have a contact information available.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    field: contact
    function: truthy
