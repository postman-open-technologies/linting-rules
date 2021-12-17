---
openapi-v3-info-title-in-kebab-case:
  description: Ensures that all OpenAPIs information title are in Kebab case.
  message: The info object title needs to be in Kebab case.
  given: $.info.title
  then:
    function: pattern
    functionOptions:
      match: ^[a-z][a-z0-9\-]*$
  type: style
  recommended: true
  formats:
    - oas2
    - oas3
  severity: error
...
openapi-v3-info-title-in-kebab-case:
  description: Ensures that all OpenAPIs information title are in Kebab case.
  message: The info object title needs to be in Kebab case.
  given: $.info.title
  then:
    function: pattern
    functionOptions:
      match: ^[a-z][a-z0-9\-]*$
  type: style
  recommended: true
  formats:
    - oas2
    - oas3
  severity: error
