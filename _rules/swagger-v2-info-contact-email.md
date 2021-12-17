---
swagger-v2-info-contact-email:
  description: Ensures that all APIs have contact email.
  message: API must have a contact email available.
  given: $.info.contact
  severity: error
  then:
    field: email
    function: truthy
...
swagger-v2-info-contact-email:
  description: Ensures that all APIs have contact email.
  message: API must have a contact email available.
  given: $.info.contact
  severity: error
  then:
    field: email
    function: truthy
