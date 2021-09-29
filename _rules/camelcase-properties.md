---
description: Properties defined inline in schema must use camelCase.
given: $..[?(@.type=="object")].properties
then:
  field: '@key'
  function: casing
  functionOptions:
    type: camel
...
given: $..[?(@.type=="object")].properties
then:
  field: '@key'
  function: casing
  functionOptions:
    type: camel