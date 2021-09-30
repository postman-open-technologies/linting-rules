---
description: |-
  WARN: This rule is under implementation and just provides an hint. Error management is a key enabler of a resilient API ecosystem. Enforcing a consistent schema for errors between different APIs,
  enables client to properly implement an error management strategy,
  with positive impacts for users.
message: Your schema doesn't seem to match RFC7807. Are you sure it is ok? {{path}}
formats:
- oas3
severity: hint
recommended: false
given: $.paths.[*].responses[?(@property.match(/^(4|5|default)/))][[schema]]
then:
  function: schema
  functionOptions:
    schema:
      type: object
      properties:
        status:
          type: integer
        title:
          type: string
        detail:
          type: string
...
description: |-
  WARN: This rule is under implementation and just provides an hint. Error management is a key enabler of a resilient API ecosystem. Enforcing a consistent schema for errors between different APIs,
  enables client to properly implement an error management strategy,
  with positive impacts for users.
message: Your schema doesn't seem to match RFC7807. Are you sure it is ok? {{path}}
formats:
- oas3
severity: hint
recommended: false
given: $.paths.[*].responses[?(@property.match(/^(4|5|default)/))][[schema]]
then:
  function: schema
  functionOptions:
    schema:
      type: object
      properties:
        status:
          type: integer
        title:
          type: string
        detail:
          type: string