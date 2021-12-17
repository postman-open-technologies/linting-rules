---
openapi-v3-security-scheme-oauth-implicit:
  description: Requires the usage of oauth implicit for security scheme.
  message: Must add oauth implicit for security scheme.
  recommended: true
  severity: error
  formats:
    - oas3
  type: style
  given: $
  then:
    field: $.components.securitySchemes.[*].flows.implicit
    function: truthy
...
openapi-v3-security-scheme-oauth-implicit:
  description: Requires the usage of oauth implicit for security scheme.
  message: Must add oauth implicit for security scheme.
  recommended: true
  severity: error
  formats:
    - oas3
  type: style
  given: $
  then:
    field: $.components.securitySchemes.[*].flows.implicit
    function: truthy
