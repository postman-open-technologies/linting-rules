---
openapi-v3-parameters-example:
  description: Ensures that that all parameters have a examples.
  message: Your parameters all need examples.
  given: $.paths.*.*.parameters[?(@.example=='query')]
  then:
    - field: example
      function: truthy
    - field: examples
      function: truthy
...
openapi-v3-parameters-example:
  description: Ensures that that all parameters have a examples.
  message: Your parameters all need examples.
  given: $.paths.*.*.parameters[?(@.example=='query')]
  then:
    - field: example
      function: truthy
    - field: examples
      function: truthy
