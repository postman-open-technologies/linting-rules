---
openapi-v3-use-of-response-schema-oneof:
  description: Checks to see if oneOf is being used as part of each schema.
  message: You should avoid using oneOf as part of your schema.
  given: $.paths.*.*[responses]..content..schema
  severity: warn
  formats:
    - oas3
  then:
    field: oneOf
    function: falsy
...
openapi-v3-use-of-response-schema-oneof:
  description: Checks to see if oneOf is being used as part of each schema.
  message: You should avoid using oneOf as part of your schema.
  given: $.paths.*.*[responses]..content..schema
  severity: warn
  formats:
    - oas3
  then:
    field: oneOf
    function: falsy
