---
openapi-v3-parameters-name-camel-case:
  description: Ensures that that all parameter names are camel case.
  message: Your parameter names should all be camel case.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    field: name
    function: casing
    functionOptions:
      type: camel
...
openapi-v3-parameters-name-camel-case:
  description: Ensures that that all parameter names are camel case.
  message: Your parameter names should all be camel case.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    field: name
    function: casing
    functionOptions:
      type: camel
