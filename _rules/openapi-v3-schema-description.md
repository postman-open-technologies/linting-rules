---
openapi-v3-schema-description:
  description: Ensure all schema properties should have a description.
  message: All schema should have descriptions.
  severity: warn
  formats:
    - oas3
  given: $.components.schemas.*
  then:
    field: description
    function: truthy
...
openapi-v3-schema-description:
  description: Ensure all schema properties should have a description.
  message: All schema should have descriptions.
  severity: warn
  formats:
    - oas3
  given: $.components.schemas.*
  then:
    field: description
    function: truthy
