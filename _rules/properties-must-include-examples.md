---
description: Object properties must include examples
message: '{{description}}; missing {{property}}'
severity: error
given: $..properties..properties.*
then:
  field: example
  function: schema
  functionOptions:
    schema:
      minItems: 1
...description: Object properties must include examples
message: '{{description}}; missing {{property}}'
severity: error
given: $..properties..properties.*
then:
  field: example
  function: schema
  functionOptions:
    schema:
      minItems: 1