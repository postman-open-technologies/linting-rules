---
info-contact-email:
  description: API must have a contact email available.
  given: $.info.contact
  severity: error
  then:
    field: email
    function: truthy
  x-status: validated
  x-tags:
    - Contact
    - Communication    
...
info-contact-email:
  description: API must have a contact email available.
  given: $.info.contact
  severity: error
  then:
    field: email
    function: truthy
  x-status: validated
  x-tags:
    - Contact
    - Communication      