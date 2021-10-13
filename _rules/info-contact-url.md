---
info-contact-url:
  description:  API must have a contact url available.
  given: $.info.contact
  severity: error
  then:
    field: url
    function: truthy
  x-status: validated
  x-tags:
    - Contact
    - Communication    
...
info-contact-url:
  description:  API must have a contact url available.
  given: $.info.contact
  severity: error
  then:
    field: url
    function: truthy
  x-status: validated
  x-tags:
    - Contact
    - Communication    