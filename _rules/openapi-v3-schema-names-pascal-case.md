---
openapi-v3-schema-names-pascal-case:
  description: Ensure all schema names are pascal case.
  message: Schema names should be pascal case.
  severity: error
  given: $.components.schemas
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
...
openapi-v3-schema-names-pascal-case:
  description: Ensure all schema names are pascal case.
  message: Schema names should be pascal case.
  severity: error
  given: $.components.schemas
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
