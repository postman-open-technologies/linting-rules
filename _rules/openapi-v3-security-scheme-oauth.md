---
openapi-v3-security-scheme-oauth:
  description: Requires the usage of OAuth for security scheme.
  message: Must add OAuth implicit for security scheme.
  recommended: true
  severity: error
  formats:
    - oas3
  type: style
  given: $
  then:
    field: $.components.securitySchemes.[*].type
    function: truthy
...
openapi-v3-security-scheme-oauth:
  description: Requires the usage of OAuth for security scheme.
  message: Must add OAuth implicit for security scheme.
  recommended: true
  severity: error
  formats:
    - oas3
  type: style
  given: $
  then:
    field: $.components.securitySchemes.[*].type
    function: truthy
