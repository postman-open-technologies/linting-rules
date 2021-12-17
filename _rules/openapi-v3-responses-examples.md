---
openapi-v3-responses-examples:
  description: Ensuring all responses have examples defined.
  message: All your responses need to have examples defined.
  severity: error
  given: $..responses..[?(@property !== 'properties' && @.examples)]
  then:
    function: schemaPath
    functionOptions:
      field: $.examples.*.value
      schemaPath: $.schema
...
openapi-v3-responses-examples:
  description: Ensuring all responses have examples defined.
  message: All your responses need to have examples defined.
  severity: error
  given: $..responses..[?(@property !== 'properties' && @.examples)]
  then:
    function: schemaPath
    functionOptions:
      field: $.examples.*.value
      schemaPath: $.schema
