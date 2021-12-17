---
swagger-v2-info-description:
  description: Ensures that all Swaggers have a information description.
  message: The info object should have a description.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    field: description
    function: truthy
...
swagger-v2-info-description:
  description: Ensures that all Swaggers have a information description.
  message: The info object should have a description.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    field: description
    function: truthy
