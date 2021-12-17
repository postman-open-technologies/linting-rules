---
openapi-v3-schema-names-snake-case:
  description: Ensure all schema names are snake case.
  message: Schema names should be snake case.
  severity: error
  given: $.components.schemas
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
...
openapi-v3-schema-names-snake-case:
  description: Ensure all schema names are snake case.
  message: Schema names should be snake case.
  severity: error
  given: $.components.schemas
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
