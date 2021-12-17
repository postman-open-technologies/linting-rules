---
openapi-v3-components-responses-pascal-case:
  description: Ensuring that all components responses are using pascal case for the name.
  message: The component responses name needs to be pascalCase.
  given: $.components.responses
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
...
openapi-v3-components-responses-pascal-case:
  description: Ensuring that all components responses are using pascal case for the name.
  message: The component responses name needs to be pascalCase.
  given: $.components.responses
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
