---
swagger-v2-schema-type:
  description: Ensuring that all schema have a type property.
  message: All schema should have a type property.
  severity: error
  formats:
    - oas2
  given: $.definitions.*
  then:
    field: type
    function: truthy
...
swagger-v2-schema-type:
  description: Ensuring that all schema have a type property.
  message: All schema should have a type property.
  severity: error
  formats:
    - oas2
  given: $.definitions.*
  then:
    field: type
    function: truthy
