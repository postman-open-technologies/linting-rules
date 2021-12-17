---
openapi-v3-info-contact-name:
  description: Ensures that all APIs have contact name.
  message: API must have a contact name available.
  given: $.info.contact
  severity: error
  then:
    field: name
    function: truthy
...
openapi-v3-info-contact-name:
  description: Ensures that all APIs have contact name.
  message: API must have a contact name available.
  given: $.info.contact
  severity: error
  then:
    field: name
    function: truthy
