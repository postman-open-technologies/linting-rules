---
message: '{{error}}'
severity: error
given: $..responses..[?(@property !== 'properties' && @.examples)]
then:
  function: schemaPath
  functionOptions:
    field: $.examples.*.value
    schemaPath: $.schema
...
severity: error
given: $..responses..[?(@property !== 'properties' && @.examples)]
then:
  function: schemaPath
  functionOptions:
    field: $.examples.*.value
    schemaPath: $.schema