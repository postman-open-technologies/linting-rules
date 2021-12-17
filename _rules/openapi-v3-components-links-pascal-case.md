---
openapi-v3-components-links-pascal-case:
  description: Ensuring that all components links are using pascal case for the key.
  message: The component links key needs to be pascalCase.
  given: $.components.links
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
...
openapi-v3-components-links-pascal-case:
  description: Ensuring that all components links are using pascal case for the key.
  message: The component links key needs to be pascalCase.
  given: $.components.links
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
