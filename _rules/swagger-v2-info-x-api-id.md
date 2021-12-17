---
swagger-v2-info-x-api-id:
  description: Ensures that all Swaggers have a information object API ID extension.
  message: The info object should have an API ID extension.
  given: $.info
  severity: error
  recommended: true
  type: style
  then:
    field: x-api-id
    function: truthy
...
swagger-v2-info-x-api-id:
  description: Ensures that all Swaggers have a information object API ID extension.
  message: The info object should have an API ID extension.
  given: $.info
  severity: error
  recommended: true
  type: style
  then:
    field: x-api-id
    function: truthy
