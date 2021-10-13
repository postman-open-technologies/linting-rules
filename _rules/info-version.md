---
info-version:
  description: The API must have version information applied.
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
  description: The API must have version information applied.
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