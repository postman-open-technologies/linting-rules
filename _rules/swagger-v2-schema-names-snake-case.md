---
swagger-v2-schema-names-snake-case:
  description: Ensure all schema names are snake case.
  message: Schema names should be snake case.
  severity: error
  given: $.definitions
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
...
swagger-v2-schema-names-snake-case:
  description: Ensure all schema names are snake case.
  message: Schema names should be snake case.
  severity: error
  given: $.definitions
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
