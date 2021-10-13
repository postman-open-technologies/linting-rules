---
info-description-max-length:
  description: The description of the API must not be greater than 250 characters.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: description
      function: length
      functionOptions: 
        max: 250      
  x-status: validated
  x-tags:
    - Info
    - Length
...
info-description-max-length:
  description: The description of the API must not be greater than 250 characters.
  given: "$.info"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
      field: description
      function: length
      functionOptions: 
        max: 250      
  x-status: validated
  x-tags:
    - Info
    - Length