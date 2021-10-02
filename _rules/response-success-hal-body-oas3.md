---
response-success-hal-body-oas3:
  description: All success responses MUST follow application/hal+json schema
  formats:
  - oas3
  given: $.paths..responses[?( @property == 200 && @property < 300 && @property !=
    204)].content[?(@property === "application/hal+json")]
  message: Response documents MUST follow application/hal+json schema {{error}}
  recommended: true
  severity: error
  then:
    field: schema
    function: schema
    functionOptions:
      schema:
        $ref: ./supermodel/adidas/api/HAL.yaml
  type: style
  x-status: draft
  x-tags:
      - Tag    
      - Adidas  
...
response-success-hal-body-oas3:
  description: All success responses MUST follow application/hal+json schema
  formats:
  - oas3
  given: $.paths..responses[?( @property == 200 && @property < 300 && @property !=
    204)].content[?(@property === "application/hal+json")]
  message: Response documents MUST follow application/hal+json schema {{error}}
  recommended: true
  severity: error
  then:
    field: schema
    function: schema
    functionOptions:
      schema:
        $ref: ./supermodel/adidas/api/HAL.yaml
  type: style
  x-status: draft
  x-tags:
      - Tag    
      - Adidas  