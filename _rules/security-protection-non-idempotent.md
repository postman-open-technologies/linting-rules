---
description: |-
  Your API should be protected by a `security` rule either at global or operation level. Operations should be protected specially when they are tied to non-idempotent HTTP methods like `POST`, `PUT`, `PATCH` and `DELETE`. This is done with one or more non-empty `security` rules. Security rules are defined in the `securityScheme` section.
message: 'The following non-idempotent operation is not protected by a `security`
  rule: {{path}}'
formats:
- oas3
severity: error
recommended: true
given:
- $.paths.*[?(@property.match(/^(post|put|patch|delete)/))]
then:
- field: security
  function: schema
  functionOptions:
    schema:
      items:
        type: object
        minProperties: 1
      minItems: 1
      type: array
...
description: |-
  Your API should be protected by a `security` rule either at global or operation level. Operations should be protected specially when they are tied to non-idempotent HTTP methods like `POST`, `PUT`, `PATCH` and `DELETE`. This is done with one or more non-empty `security` rules. Security rules are defined in the `securityScheme` section.
message: 'The following non-idempotent operation is not protected by a `security`
  rule: {{path}}'
formats:
- oas3
severity: error
recommended: true
given:
- $.paths.*[?(@property.match(/^(post|put|patch|delete)/))]
then:
- field: security
  function: schema
  functionOptions:
    schema:
      items:
        type: object
        minProperties: 1
      minItems: 1
      type: array