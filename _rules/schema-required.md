---
schema-required:
  description: All schemas properties should have a required.
  message: Should have schema property {{ property }}.
  severity: warn
  formats:
  - oas3
  given: $.components.schemas.*
  then:
      field: required
      function: truthy
  x-status: validated
  x-tags:
      - Schema         
...
schema-required:
  description: All schemas properties should have a required.
  message: Should have schema property {{ property }}.
  severity: warn
  formats:
  - oas3
  given: $.components.schemas.*
  then:
      field: required
      function: truthy
  x-status: validated
  x-tags:
      - Schema  