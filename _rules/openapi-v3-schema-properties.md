---
openapi-v3-schema-properties:
  description: Ensuring that all schema should have properties.
  message: All of your schema need to have properties.
  severity: error
  formats:
    - oas3
  given: $.components.schemas.*
  then:
    field: properties
    function: truthy
...
openapi-v3-schema-properties:
  description: Ensuring that all schema should have properties.
  message: All of your schema need to have properties.
  severity: error
  formats:
    - oas3
  given: $.components.schemas.*
  then:
    field: properties
    function: truthy
