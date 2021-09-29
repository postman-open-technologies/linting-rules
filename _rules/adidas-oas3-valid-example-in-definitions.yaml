---
description: Examples must be valid against their defined schema.
formats:
- oas3
given: $..definitions..[?(@property !== 'properties' && @.example && (@.type || @.format
  || @.$ref))]
message: '{{error}}'
recommended: true
severity: 0
then:
  function: schemaPath
  functionOptions:
    field: example
    schemaPath: $
type: validation
...description: Examples must be valid against their defined schema.
formats:
- oas3
given: $..definitions..[?(@property !== 'properties' && @.example && (@.type || @.format
  || @.$ref))]
message: '{{error}}'
recommended: true
severity: 0
then:
  function: schemaPath
  functionOptions:
    field: example
    schemaPath: $
type: validation