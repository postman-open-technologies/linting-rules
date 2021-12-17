---
openapi-v3-info-description-max-length:
  description: Ensures that all APIs descriptions are under a specific length.
  message: The info object description should be less than 250 characters.
  given: $.info
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
...
openapi-v3-info-description-max-length:
  description: Ensures that all APIs descriptions are under a specific length.
  message: The info object description should be less than 250 characters.
  given: $.info
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
