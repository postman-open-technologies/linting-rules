---
info-version:
  description: "Mus have #/info/version."
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: version
      function: truthy  
  x-status: validated
  x-tags:
    - Versioning
    - Info
...
info-version:
  description: "Mus have #/info/version."
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: version
      function: truthy  
  x-status: validated
  x-tags:
    - Versioning
    - Info  