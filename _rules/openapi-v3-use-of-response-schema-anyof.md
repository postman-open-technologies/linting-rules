---
openapi-v3-use-of-response-schema-anyof:
  description: Checks to see if anyOf is being used as part of each schema.
  message: You should avoid using anyOf as part of your schema.
  given: $.paths.*.*[responses]..content..schema
  severity: warn
  formats:
    - oas3
  then:
    field: anyOf
    function: falsy
...
openapi-v3-use-of-response-schema-anyof:
  description: Checks to see if anyOf is being used as part of each schema.
  message: You should avoid using anyOf as part of your schema.
  given: $.paths.*.*[responses]..content..schema
  severity: warn
  formats:
    - oas3
  then:
    field: anyOf
    function: falsy
