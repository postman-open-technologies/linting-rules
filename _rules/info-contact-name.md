---
info-contact-name:
  description:  API must have a contact name available.
  given: $.info.contact
  severity: error
  then:
    field: name
    function: truthy
  x-status: validated
  x-tags:
    - Contact
    - Communication    
...
info-contact-name:
  description:  API must have a contact name available.
  given: $.info.contact
  severity: error
  then:
    field: name
    function: truthy
  x-status: validated
  x-tags:
    - Contact
    - Communication 