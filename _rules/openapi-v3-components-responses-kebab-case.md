---
openapi-v3-components-responses-kebab-case:
  description: Ensuring that all components responses are using kebab case for the name.
  message: The component responses name needs to be kebabCase.
  given: $.components.responses
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: kebab
...
openapi-v3-components-responses-kebab-case:
  description: Ensuring that all components responses are using kebab case for the name.
  message: The component responses name needs to be kebabCase.
  given: $.components.responses
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: kebab
