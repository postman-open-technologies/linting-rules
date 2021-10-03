---
schema-names-pascal-case:
  description: Schema names should be pascal case.
  message: Schema name should be pascal case.
  severity: error
  given: $.components.schemas
  then:
    field: "@key"
    function: casing
    functionOptions:
      type: pascal
  x-status: validated
  x-tags:
      - Schema
      - Casing          
...
schema-names-pascal-case:
  description: Schema names should be pascal case.
  message: Schema name should be pascal case.
  severity: error
  given: $.components.schemas
  then:
    field: "@key"
    function: casing
    functionOptions:
      type: pascal
  x-status: validated
  x-tags:
      - Schema
      - Casing       