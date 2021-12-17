---
openapi-v3-components-callbacks-kebab-case:
  description: Ensuring that all components callbacks are using kebab case for the key.
  message: The component callback key needs to be kebabCase.
  given: $.components.callbacks
  severity: error
  formats:
    - oas3
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: kebab
...
openapi-v3-components-callbacks-kebab-case:
  description: Ensuring that all components callbacks are using kebab case for the key.
  message: The component callback key needs to be kebabCase.
  given: $.components.callbacks
  severity: error
  formats:
    - oas3
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: kebab
