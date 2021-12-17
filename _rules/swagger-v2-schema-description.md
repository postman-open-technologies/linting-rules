---
swagger-v2-schema-description:
  description: Ensure all schema properties should have a description.
  message: All schema should have descriptions.
  severity: warn
  formats:
    - oas2
  given: $.definitions.*
  then:
    field: description
    function: truthy
...
swagger-v2-schema-description:
  description: Ensure all schema properties should have a description.
  message: All schema should have descriptions.
  severity: warn
  formats:
    - oas2
  given: $.definitions.*
  then:
    field: description
    function: truthy
