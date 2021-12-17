---
openapi-v3-components-examples-pascal-case:
  description: Ensuring that all components example are using pascal case for the key.
  message: The component example key needs to be pascalCase.
  given: $.components.examples
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
...
openapi-v3-components-examples-pascal-case:
  description: Ensuring that all components example are using pascal case for the key.
  message: The component example key needs to be pascalCase.
  given: $.components.examples
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
