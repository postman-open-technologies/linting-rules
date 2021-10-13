---
info-summary:
  description: The API must have a summary applied.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: summary
      function: truthy  
  x-status: validated
  x-tags:
    - Summary
    - Info
...
info-summary:
  description: The API must have a summary applied.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: summary
      function: truthy  
  x-status: validated
  x-tags:
    - Summary
    - Info