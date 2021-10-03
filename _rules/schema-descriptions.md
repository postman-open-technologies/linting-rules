---
schema-should-have-description-or-title-oas3:
  description: All schemas should have a description or title.
  message: Schema should have a description or title.
  severity: warn
  formats:
  - oas3
  given: $..properties.*
  then:
      field: description
      function: truthy
  x-status: draft
  x-tags:
      - Tag         
...
schema-should-have-description-or-title-oas3:
  description: All schemas should have a description or title.
  message: Schema should have a description or title.
  severity: warn
  formats:
  - oas3
  given: $..properties.*
  then:
      field: description
      function: truthy
  x-status: draft
  x-tags:
      - Tag      