---
paths-ref-must-be-file:
  description: Endpoint must a $ref to a file in endpoints/
  message: '{{description}}; {{value}} incorrect'
  severity: error
  resolved: false
  given: $.paths.*.$ref
  then:
    function: pattern
    functionOptions:
      match: ^endpoints\/.*yml$
...
paths-ref-must-be-file:
  description: Endpoint must a $ref to a file in endpoints/
  message: '{{description}}; {{value}} incorrect'
  severity: error
  resolved: false
  given: $.paths.*.$ref
  then:
    function: pattern
    functionOptions:
      match: ^endpoints\/.*yml$