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