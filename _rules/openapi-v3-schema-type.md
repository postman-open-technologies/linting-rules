---
openapi-v3-schema-type:
  description: Ensuring that all schema have a type property.
  message: All schema should have a type property.
  severity: error
  formats:
    - oas3
  given: $.components.schemas.*
  then:
    field: type
    function: truthy
...
openapi-v3-schema-type:
  description: Ensuring that all schema have a type property.
  message: All schema should have a type property.
  severity: error
  formats:
    - oas3
  given: $.components.schemas.*
  then:
    field: type
    function: truthy
