---
swagger-v2-schema-names-camel-case:
  description: Ensure all schema names are camel case.
  message: Schema names should be camel case.
  severity: error
  given: $.definitions
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
...
swagger-v2-schema-names-camel-case:
  description: Ensure all schema names are camel case.
  message: Schema names should be camel case.
  severity: error
  given: $.definitions
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
