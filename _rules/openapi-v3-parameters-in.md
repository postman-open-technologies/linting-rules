---
openapi-v3-parameters-in:
  description: Ensures that that all parameters have an in property.
  message: Your parameters all need to have in properties.
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: in
    function: truthy
...
openapi-v3-parameters-in:
  description: Ensures that that all parameters have an in property.
  message: Your parameters all need to have in properties.
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: in
    function: truthy
