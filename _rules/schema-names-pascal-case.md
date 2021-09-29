---
description: Schema names MUST be written in PascalCase
message: component '{{property}}' {{error}}
recommended: true
type: style
severity: error
given: $.components.schemas.*~
then:
  function: casing
  functionOptions:
    type: pascal
...description: Schema names MUST be written in PascalCase
message: component '{{property}}' {{error}}
recommended: true
type: style
severity: error
given: $.components.schemas.*~
then:
  function: casing
  functionOptions:
    type: pascal