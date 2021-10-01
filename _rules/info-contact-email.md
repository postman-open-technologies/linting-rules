---
info-contact-email:
  description: Should have a contact email.
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
  description: Should have a contact email.
  given: $.info.contact
  severity: error
  then:
    field: email
    function: truthy
  x-status: validated
  x-tags:
    - Contact
    - Communication    