---
description: Examples must be valid against their defined schema.
message: '{{error}}'
recommended: true
formats:
- oas3
severity: 0
type: validation
given: $..parameters..[?(@.in == 'body')]..[?(@property !== 'properties' && @.example
  && ( @.type || @.format || @.$ref ))]
then:
  function: schemaPath
  functionOptions:
    field: example
    schemaPath: $
...
message: '{{error}}'
recommended: true
formats:
- oas3
severity: 0
type: validation
given: $..parameters..[?(@.in == 'body')]..[?(@property !== 'properties' && @.example
  && ( @.type || @.format || @.$ref ))]
then:
  function: schemaPath
  functionOptions:
    field: example
    schemaPath: $