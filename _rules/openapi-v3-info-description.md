---
openapi-v3-info-description:
  description: Ensures that all OpenAPIs have a information description.
  message: The info object should have a description.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    field: description
    function: truthy
...
openapi-v3-info-description:
  description: Ensures that all OpenAPIs have a information description.
  message: The info object should have a description.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    field: description
    function: truthy
