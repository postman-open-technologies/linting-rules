---
info-title-max-length:
  description: The title of the API must not be more than 50 characters.
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
        max: 50      
  x-status: validated
  x-tags:
    - Info
    - Length
...
info-title-max-length:
  description: The title of the API must not be more than 50 characters.
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
        max: 50      
  x-status: validated
  x-tags:
    - Info
    - Length