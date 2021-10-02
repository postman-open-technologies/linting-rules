---
parameters-schema:
  description: "Parameters must have a schema."
  given: $.paths.*.*.parameters[?(@.schema=='query')]
  then:
    field: schema
    function: truthy
  x-status: validated
  x-tags:
    - Parameters      
    - Schema  
...
parameters-schema:
  description: "Parameters must have a schema."
  given: $.paths.*.*.parameters[?(@.schema=='query')]
  then:
    field: schema
    function: truthy
  x-status: validated
  x-tags:
    - Parameters      
    - Schema       