---
schema-properties-camelcase:
  description: Properties defined inline in schema must use camelCase.
  given: $..[?(@.type=="object")].properties
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel
...
schema-properties-camelcase:
  description: Properties defined inline in schema must use camelCase.
  given: $..[?(@.type=="object")].properties
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: camel