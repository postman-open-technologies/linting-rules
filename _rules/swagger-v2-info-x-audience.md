---
swagger-v2-info-x-audience:
  description: Ensures that all Swaggers have a information object audience extension.
  message: The info object should have an audience extension.
  severity: error
  given: $.info
  then:
    field: x-audience
    function: truthy
...
swagger-v2-info-x-audience:
  description: Ensures that all Swaggers have a information object audience extension.
  message: The info object should have an audience extension.
  severity: error
  given: $.info
  then:
    field: x-audience
    function: truthy
