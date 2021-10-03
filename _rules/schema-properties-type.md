---
schema-properties-type:
  description: All schemas properties should have a type.
  message: Should have schema property {{ property }}.
  severity: warn
  formats:
  - oas3
  given: $..properties.*
  then:
      field: type
      function: truthy
  x-status: validated
  x-tags:
      - Schema         
...
schema-properties-type:
  description: All schemas properties should have a type.
  message: Should have schema property {{ property }}.
  severity: warn
  formats:
  - oas3
  given: $..properties.*
  then:
      field: type
      function: truthy
  x-status: validated
  x-tags:
      - Schema  