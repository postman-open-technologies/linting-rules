---
openapi-v3-components-examples-kebab-case:
  description: Ensuring that all components example are using kebab case for the key.
  message: The component example key needs to be kebabCase.
  given: $.components.examples
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: kebab
...
openapi-v3-components-examples-kebab-case:
  description: Ensuring that all components example are using kebab case for the key.
  message: The component example key needs to be kebabCase.
  given: $.components.examples
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: kebab
