---
openapi-v3-info-title-max-length:
  description: Ensures that all OpenAPIs information titles are not longer than 50
    characters.
  message: The info object title should not be more than 50 characters.
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
...
openapi-v3-info-title-max-length:
  description: Ensures that all OpenAPIs information titles are not longer than 50
    characters.
  message: The info object title should not be more than 50 characters.
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

