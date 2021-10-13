---
info-license:
  description: API must have a license applied.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: license
      function: truthy  
  x-status: validated
  x-tags:
    - Licensing
    - Legal
...
info-license:
  description: API must have a license applied.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: license
      function: truthy  
  x-status: validated
  x-tags:
    - Licensing
    - Legal  