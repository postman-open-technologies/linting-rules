---
description: Every request SHOULD support `application/json` media type
formats:
- oas2
severity: warn
message: '{{description}}: {{error}}'
recommended: true
given: $..consumes
then:
  function: schema
  functionOptions:
    schema:
      type: array
      contains:
        type: string
        enum:
        - application/json
...description: Every request SHOULD support `application/json` media type
formats:
- oas2
severity: warn
message: '{{description}}: {{error}}'
recommended: true
given: $..consumes
then:
  function: schema
  functionOptions:
    schema:
      type: array
      contains:
        type: string
        enum:
        - application/json