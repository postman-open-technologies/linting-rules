---
description: Endpoint must a $ref
message: '{{description}}; {{property}} incorrect'
severity: error
resolved: false
given: $.paths.*
then:
- field: $ref
  function: truthy
...
message: '{{description}}; {{property}} incorrect'
severity: error
resolved: false
given: $.paths.*
then:
- field: $ref
  function: truthy