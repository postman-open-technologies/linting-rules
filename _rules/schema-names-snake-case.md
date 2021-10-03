---
schema-names-snake-case:
  description: Schema names should be snake case.
  message: Schema name should be snake case.
  severity: error
  given: $.components.schemas
  then:
    field: "@key"
    function: casing
    functionOptions:
      type: snake
  x-status: validated
  x-tags:
      - Schema
      - Casing          
...
schema-names-snake-case:
  description: Schema names should be snake case.
  message: Schema name should be snake case.
  severity: error
  given: $.components.schemas
  then:
    field: "@key"
    function: casing
    functionOptions:
      type: snake
  x-status: validated
  x-tags:
      - Schema
      - Casing       