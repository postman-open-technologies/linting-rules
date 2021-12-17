---
swagger-v2-schema-properties:
  description: Ensuring that all schema should have properties.
  message: All of your schema need to have properties.
  severity: error
  formats:
    - oas2
  given: $.definitions.*
  then:
    field: properties
    function: truthy
...
swagger-v2-schema-properties:
  description: Ensuring that all schema should have properties.
  message: All of your schema need to have properties.
  severity: error
  formats:
    - oas2
  given: $.definitions.*
  then:
    field: properties
    function: truthy
