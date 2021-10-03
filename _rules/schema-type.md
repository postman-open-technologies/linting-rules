---
schema-type:
  description: All schemas should have a type.
  message: Should have schema {{ property }}.
  severity: error
  formats:
    - oas3
  given: $.components.schemas.*
  then:
      field: type
      function: truthy
  x-status: validated
  x-tags:
      - Schema         
...
schema-type:
  description: All schemas should have a type.
  message: Should have schema {{ property }}.
  severity: error
  formats:
    - oas3
  given: $.components.schemas.*
  then:
      field: type
      function: truthy
  x-status: validated
  x-tags:
      - Schema  