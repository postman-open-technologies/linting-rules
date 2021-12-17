---
swagger-v2-parameters-schema-type-array:
  description: Ensures that that all parameters of schema type array have items defined.
  message: Your parameter schema should have an items property if it is an array.
  given: $.paths.*.*.parameters[?(@.in=='query')].schema[?(@.type=='array')]
  then:
    field: items
    function: truthy
...
swagger-v2-parameters-schema-type-array:
  description: Ensures that that all parameters of schema type array have items defined.
  message: Your parameter schema should have an items property if it is an array.
  given: $.paths.*.*.parameters[?(@.in=='query')].schema[?(@.type=='array')]
  then:
    field: items
    function: truthy
