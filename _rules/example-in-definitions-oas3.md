---
example-in-definitions-oas2:
  description: Examples must be valid against their defined schema.
  formats:
  - oas2
  given: $..definitions..[?(@property !== 'properties' && @.example && (@.type ||
    @.format || @.$ref))]
  message: '{{error}}'
  recommended: true
  severity: 0
  then:
    function: schemaPath
    functionOptions:
      field: example
      schemaPath: $
  type: validation
  x-status: draft
  x-tags:
    - Tag
    - Adidas  
...
example-in-definitions-oas2:
  description: Examples must be valid against their defined schema.
  formats:
  - oas2
  given: $..definitions..[?(@property !== 'properties' && @.example && (@.type ||
    @.format || @.$ref))]
  message: '{{error}}'
  recommended: true
  severity: 0
  then:
    function: schemaPath
    functionOptions:
      field: example
      schemaPath: $
  type: validation
  x-status: draft
  x-tags:
    - Tag
    - Adidas  