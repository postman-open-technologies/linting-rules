---
schema-properties-names-camel-case:
  description: Schema property names should be camel case.
  message: Schema name should be camel case.
  severity: error
  given: $..properties.*
  then:
    field: "@key"
    function: casing
    functionOptions:
      type: camel
  x-status: validated
  x-tags:
      - Schema
      - Casing          
...
schema-properties-names-camel-case:
  description: Schema property names should be camel case.
  message: Schema name should be camel case.
  severity: error
  given: $..properties.*
  then:
    field: "@key"
    function: casing
    functionOptions:
      type: camel
  x-status: validated
  x-tags:
      - Schema
      - Casing    