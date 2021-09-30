---
description: |-
  Your API should be protected by a `security` rule either at global or operation level. Operations should be protected specially when they are tied to non-idempotent HTTP methods like `POST`, `PUT`, `PATCH` and `DELETE`. This is done with one or more non-empty `security` rules.
message: 'The following operation is not protected by a `security` rule: {{path}}'
formats:
- oas3
severity: info
recommended: true
given:
- $.paths.*.get
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
  Your API should be protected by a `security` rule either at global or operation level. Operations should be protected specially when they are tied to non-idempotent HTTP methods like `POST`, `PUT`, `PATCH` and `DELETE`. This is done with one or more non-empty `security` rules.
message: 'The following operation is not protected by a `security` rule: {{path}}'
formats:
- oas3
severity: info
recommended: true
given:
- $.paths.*.get
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