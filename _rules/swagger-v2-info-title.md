---
swagger-v2-info-title:
  description: Ensures that all Swaggers have a information object title.
  message: The info object should have a title.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    field: title
    function: truthy
...
swagger-v2-info-title:
  description: Ensures that all Swaggers have a information object title.
  message: The info object should have a title.
  given: $.info
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    field: title
    function: truthy
