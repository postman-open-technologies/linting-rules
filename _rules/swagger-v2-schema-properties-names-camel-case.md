---
swagger-v2-schema-properties-names-camel-case:
  description: Ensuring that schema property names are camel case.
  message: All schema property names should be camel case.
  severity: error
  given: $.definitions.properties.*
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
...
swagger-v2-schema-properties-names-camel-case:
  description: Ensuring that schema property names are camel case.
  message: All schema property names should be camel case.
  severity: error
  given: $.definitions.properties.*
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
