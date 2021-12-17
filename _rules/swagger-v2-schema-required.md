---
swagger-v2-schema-required:
  description: Ensuring that all schema have a required property.
  message: All of your schema need to have a required property.
  severity: warn
  formats:
    - oas2
  given: $.definitions.*
  then:
    field: required
    function: truthy
...
swagger-v2-schema-required:
  description: Ensuring that all schema have a required property.
  message: All of your schema need to have a required property.
  severity: warn
  formats:
    - oas2
  given: $.definitions.*
  then:
    field: required
    function: truthy
