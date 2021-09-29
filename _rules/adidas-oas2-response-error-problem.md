---
description: All error responses MUST be of media type `application/problem+json`
formats:
- oas2
given: $.paths..responses[?( @property >= 400 && @property < 600 )]
message: 'Error response document MUST follow application/problem+json: {{error}}'
recommended: true
severity: error
then:
  field: schema.example
  function: schema
  functionOptions:
    schema:
      $ref: ./supermodel/adidas/api/ProblemDetail.yaml
type: style
...
formats:
- oas2
given: $.paths..responses[?( @property >= 400 && @property < 600 )]
message: 'Error response document MUST follow application/problem+json: {{error}}'
recommended: true
severity: error
then:
  field: schema.example
  function: schema
  functionOptions:
    schema:
      $ref: ./supermodel/adidas/api/ProblemDetail.yaml
type: style