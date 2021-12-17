---
swagger-v2-info-contact-url:
  description: Ensures that all APIs have contact URL.
  message: API must have a contact URL available.
  given: $.info.contact
  severity: error
  then:
    field: url
    function: truthy
...
swagger-v2-info-contact-url:
  description: Ensures that all APIs have contact URL.
  message: API must have a contact URL available.
  given: $.info.contact
  severity: error
  then:
    field: url
    function: truthy
