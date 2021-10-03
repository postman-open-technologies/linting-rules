---
schema-properties-minimum:
  description: All schemas properties should have a minimum.
  message: Should have schema property {{ property }}.
  severity: warn
  formats:
  - oas3
  given: $..properties.*
  then:
      field: minimum
      function: truthy
  x-status: validated
  x-tags:
      - Schema         
...
schema-properties-minimum:
  description: All schemas properties should have a minimum.
  message: Should have schema property {{ property }}.
  severity: warn
  formats:
  - oas3
  given: $..properties.*
  then:
      field: minimum
      function: truthy
  x-status: validated
  x-tags:
      - Schema  