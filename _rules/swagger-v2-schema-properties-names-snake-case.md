---
swagger-v2-schema-properties-names-snake-case:
  description: Ensuring that schema property names are snake case.
  message: All schema property names should be snake case.
  severity: error
  given: $.definitions.properties.*
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
...
swagger-v2-schema-properties-names-snake-case:
  description: Ensuring that schema property names are snake case.
  message: All schema property names should be snake case.
  severity: error
  given: $.definitions.properties.*
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: snake
