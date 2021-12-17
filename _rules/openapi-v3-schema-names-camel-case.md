---
openapi-v3-schema-names-camel-case:
  description: Ensure all schema names are camel case.
  message: Schema names should be camel case.
  severity: error
  given: $.components.schemas
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
...
openapi-v3-schema-names-camel-case:
  description: Ensure all schema names are camel case.
  message: Schema names should be camel case.
  severity: error
  given: $.components.schemas
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
