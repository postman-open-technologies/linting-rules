---
openapi-v3-components-links-kebab-case:
  description: Ensuring that all components links are using kebab case for the key.
  message: The component links key needs to be kebabCase.
  given: $.components.links
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: kebab
...
openapi-v3-components-links-kebab-case:
  description: Ensuring that all components links are using kebab case for the key.
  message: The component links key needs to be kebabCase.
  given: $.components.links
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: kebab
