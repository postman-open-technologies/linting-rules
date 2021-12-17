---
openapi-v3-info-summary-max-length:
  description: Ensures that all OpenAPIs information object summary are not too long.
  message: The info object summary should be less than 50 characters.
  given: $.info
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
...
openapi-v3-info-summary-max-length:
  description: Ensures that all OpenAPIs information object summary are not too long.
  message: The info object summary should be less than 50 characters.
  given: $.info
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
