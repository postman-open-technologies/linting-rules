---
info-contact:
  description:  API must have a contact information available.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: contact
      function: truthy  
  x-status: validated
  x-tags:
    - Contact
    - Communication
...
info-contact:
  description:  API must have a contact information available.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: contact
      function: truthy  
  x-status: validated
  x-tags:
    - Contact
    - Communication  