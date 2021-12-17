---
openapi-v3-parameters-schema-type:
  description: Ensures that that all parameters have a schema type.
  message: Your parameter should all schema types.
  given: $.paths.*.*.parameters[?(@.in=='query')].schema
  then:
    field: type
    function: truthy
...
openapi-v3-parameters-schema-type:
  description: Ensures that that all parameters have a schema type.
  message: Your parameter should all schema types.
  given: $.paths.*.*.parameters[?(@.in=='query')].schema
  then:
    field: type
    function: truthy
