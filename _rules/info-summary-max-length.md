---
info-summary-max-length:
  description: The summary for the API should not be more than 50 characters in length.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: summary
      function: length
      functionOptions: 
        max: 50      
  x-status: validated
  x-tags:
    - Info
    - Length
...
info-summary-max-length:
  description: The summary for the API should not be more than 50 characters in length.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: summary
      function: length
      functionOptions: 
        max: 50      
  x-status: validated
  x-tags:
    - Info
    - Length