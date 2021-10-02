---
endpoint-must-be-ref:
  description: Endpoint must a $ref
  message: '{{description}}; {{property}} incorrect'
  severity: error
  resolved: false
  given: $.paths.*
  then:
  - field: $ref
    function: truthy
  x-status: draft
  x-tags:
      - Tag      
...
endpoint-must-be-ref:
  description: Endpoint must a $ref
  message: '{{description}}; {{property}} incorrect'
  severity: error
  resolved: false
  given: $.paths.*
  then:
  - field: $ref
    function: truthy
  x-status: draft
  x-tags:
      - Tag      