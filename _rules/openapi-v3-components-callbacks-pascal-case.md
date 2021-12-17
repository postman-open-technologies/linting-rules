---
openapi-v3-components-callbacks-pascal-case:
  description: Ensuring that all components callbacks are using pascal case for the key.
  message: The component callback key needs to be pascalCase.
  given: $.components.callbacks
  severity: error
  formats:
    - oas3
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
...
openapi-v3-components-callbacks-pascal-case:
  description: Ensuring that all components callbacks are using pascal case for the key.
  message: The component callback key needs to be pascalCase.
  given: $.components.callbacks
  severity: error
  formats:
    - oas3
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
