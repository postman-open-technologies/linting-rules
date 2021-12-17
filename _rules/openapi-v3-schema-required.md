---
openapi-v3-schema-required:
  description: Ensuring that all schema have a required property.
  message: All of your schema need to have a required property.
  severity: warn
  formats:
    - oas3
  given: $.components.schemas.*
  then:
    field: required
    function: truthy
...
openapi-v3-schema-required:
  description: Ensuring that all schema have a required property.
  message: All of your schema need to have a required property.
  severity: warn
  formats:
    - oas3
  given: $.components.schemas.*
  then:
    field: required
    function: truthy
