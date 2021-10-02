---
responses-examples:
  message: '{{error}}'
  severity: error
  given: $..responses..[?(@property !== 'properties' && @.examples)]
  then:
    function: schemaPath
    functionOptions:
      field: $.examples.*.value
      schemaPath: $.schema
  x-status: draft
  x-tags:
      - Tag          
...
responses-examples:
  message: '{{error}}'
  severity: error
  given: $..responses..[?(@property !== 'properties' && @.examples)]
  then:
    function: schemaPath
    functionOptions:
      field: $.examples.*.value
      schemaPath: $.schema
  x-status: draft
  x-tags:
      - Tag          