---
info-title-max-length:
  description: "The title must not be too long."
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: title
      function: length
      functionOptions: 
        max: 20      
  x-status: validated
  x-tags:
    - Info
    - Length
...
info-title-max-length:
  description: "The title must not be too long."
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: title
      function: length
      functionOptions: 
        max: 20      
  x-status: validated
  x-tags:
    - Info
    - Length 