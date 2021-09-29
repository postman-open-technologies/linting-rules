---
description: ALL requests MUST go through `https` protocol only
recommended: true
severity: error
formats:
- oas2
type: style
message: Schemes MUST be https and no other value is allowed.
given: $.schemes
then:
  function: schema
  functionOptions:
    schema:
      type: array
      items:
        type: string
        enum:
        - https
      maxItems: 1
...
recommended: true
severity: error
formats:
- oas2
type: style
message: Schemes MUST be https and no other value is allowed.
given: $.schemes
then:
  function: schema
  functionOptions:
    schema:
      type: array
      items:
        type: string
        enum:
        - https
      maxItems: 1