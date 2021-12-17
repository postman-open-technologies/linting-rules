---
openapi-v3-responses-schema-object:
  description: Ensuring all responses have a schema defined.
  message: All your responses need to have a schema defined.
  severity: error
  given: $.paths.*.*[responses]..content..schema
  then:
    function: is-object-schema
...
openapi-v3-responses-schema-object:
  description: Ensuring all responses have a schema defined.
  message: All your responses need to have a schema defined.
  severity: error
  given: $.paths.*.*[responses]..content..schema
  then:
    function: is-object-schema
