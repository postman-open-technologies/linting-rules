---
schema-properties-maximum:
  description: All schemas properties should have a maximum.
  message: Should have schema property {{ property }}.
  severity: warn
  formats:
  - oas3
  given: $..properties.*
  then:
      field: maximum
      function: truthy
  x-status: validated
  x-tags:
      - Schema         
...
schema-properties-maximum:
  description: All schemas properties should have a maximum.
  message: Should have schema property {{ property }}.
  severity: warn
  formats:
  - oas3
  given: $..properties.*
  then:
      field: maximum
      function: truthy
  x-status: validated
  x-tags:
      - Schema  