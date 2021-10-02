---
parameters-schema-type:
  description: "Parameters must have a schema."
  given: $.paths.*.*.parameters[?(@.schema=='query')].schema
  then:
    field: type
    function: truthy
  x-status: validated
  x-tags:
    - Parameters      
    - Schema  
...
parameters-schema-type:
  description: "Parameters must have a schema."
  given: $.paths.*.*.parameters[?(@.schema=='query')].schema
  then:
    field: type
    function: truthy
  x-status: validated
  x-tags:
    - Parameters      
    - Schema       