---
schema-properties-description:
  description: All schemas properties should have a description.
  message: Should have schema property {{ property }}.
  severity: warn
  formats:
  - oas3
  given: $.components.schemas.*
  then:
      field: description
      function: truthy
  x-status: validated
  x-tags:
      - Schema         
...
schema-properties-description:
  description: All schemas properties should have a description.
  message: Should have schema property {{ property }}.
  severity: warn
  formats:
  - oas3
  given: $.components.schemas.*
  then:
      field: description
      function: truthy
  x-status: validated
  x-tags:
      - Schema  