---
response-success-and-problem-oas3:
  description: All success responses MUST be of media type application/hal+json or
    application/problem+json
  formats:
  - oas3
  given: $.paths..responses[?( @property == 200 )].content[*]~
  message: Response documents MUST be of application/hal+json or application/problem+json
    media types {{error}}
  recommended: true
  severity: error
  then:
    function: enumeration
    functionOptions:
      values:
      - application/hal+json
      - application/problem+json
  x-tags:
    - Adidas      
...
response-success-and-problem-oas3:
  description: All success responses MUST be of media type application/hal+json or
    application/problem+json
  formats:
  - oas3
  given: $.paths..responses[?( @property == 200 )].content[*]~
  message: Response documents MUST be of application/hal+json or application/problem+json
    media types {{error}}
  recommended: true
  severity: error
  then:
    function: enumeration
    functionOptions:
      values:
      - application/hal+json
      - application/problem+json
  x-tags:
    - Adidas   