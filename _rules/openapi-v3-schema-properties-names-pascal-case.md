---
openapi-v3-schema-properties-names-pascal-case:
  description: Ensuring that schema property names are pascal case.
  message: All schema property names should be pascal case.
  severity: error
  given: $..properties.*
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
...
openapi-v3-schema-properties-names-pascal-case:
  description: Ensuring that schema property names are pascal case.
  message: All schema property names should be pascal case.
  severity: error
  given: $..properties.*
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
