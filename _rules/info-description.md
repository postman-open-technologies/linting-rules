---
info-description:
  description: API must have a description available.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: description
      function: truthy  
  x-status: validated
  x-tags:
    - Info
    - Documentation
...
info-description:
  description: API must have a description available.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: description
      function: truthy  
  x-status: validated
  x-tags:
    - Info
    - Documentation  