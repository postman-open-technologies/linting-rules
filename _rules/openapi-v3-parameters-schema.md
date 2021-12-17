---
openapi-v3-parameters-schema:
  description: Ensures that that all parameters have a schema.
  message: Your parameter should all have a schema defined.
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: schema
    function: truthy
...
openapi-v3-parameters-schema:
  description: Ensures that that all parameters have a schema.
  message: Your parameter should all have a schema defined.
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: schema
    function: truthy
