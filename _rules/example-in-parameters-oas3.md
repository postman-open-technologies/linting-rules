---
example-in-parameters-oas3:
  description: Examples must be valid against their defined schema.
  formats:
  - oas3
  given: $..parameters..[?(@.in == 'body')]..[?(@property !== 'properties' && @.example && ( @.type || @.format || @.$ref ))]
  message: '{{error}}'
  recommended: true
  severity: 0
  then:
    function: schemaPath
    functionOptions:
      field: example
      schemaPath: $
  type: validation
  x-tags:
    - Adidas  
...
example-in-parameters-oas3:
  description: Examples must be valid against their defined schema.
  formats:
  - oas3
  given: $..parameters..[?(@.in == 'body')]..[?(@property !== 'properties' && @.example && ( @.type || @.format || @.$ref ))]
  message: '{{error}}'
  recommended: true
  severity: 0
  then:
    function: schemaPath
    functionOptions:
      field: example
      schemaPath: $
  type: validation
  x-tags:
    - Adidas 