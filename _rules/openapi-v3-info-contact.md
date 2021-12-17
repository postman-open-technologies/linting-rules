---
openapi-v3-info-contact:
  description: Ensures that all APIs have contact information.
  message: API must have a contact information available.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    field: contact
    function: truthy
...
openapi-v3-info-contact:
  description: Ensures that all APIs have contact information.
  message: API must have a contact information available.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    field: contact
    function: truthy
