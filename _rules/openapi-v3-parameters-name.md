---
openapi-v3-parameters-name:
  description: Ensures that that all parameters have a name.
  message: Your parameter should all have names.
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: name
    function: truthy
...
openapi-v3-parameters-name:
  description: Ensures that that all parameters have a name.
  message: Your parameter should all have names.
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: name
    function: truthy
