---
swagger-v2-schema-names-pascal-case:
  description: Ensure all schema names are pascal case.
  message: Schema names should be pascal case.
  severity: error
  given: $.definitions
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
...
swagger-v2-schema-names-pascal-case:
  description: Ensure all schema names are pascal case.
  message: Schema names should be pascal case.
  severity: error
  given: $.definitions
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
