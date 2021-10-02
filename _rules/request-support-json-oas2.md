---
request-support-json:
  description: Every request SHOULD support application/json media type
  formats:
  - oas2
  given: $..consumes
  message: '{{description}} {{error}}'
  recommended: true
  severity: warn
  then:
    function: schema
    functionOptions:
      schema:
        contains:
          enum:
          - application/json
          type: string
        type: array
  x-status: draft
  x-tags:
      - Tag    
      - Adidas
...
request-support-json:
  description: Every request SHOULD support application/json media type
  formats:
  - oas2
  given: $..consumes
  message: '{{description}} {{error}}'
  recommended: true
  severity: warn
  then:
    function: schema
    functionOptions:
      schema:
        contains:
          enum:
          - application/json
          type: string
        type: array
  x-status: draft
  x-tags:
      - Tag    
      - Adidas        
