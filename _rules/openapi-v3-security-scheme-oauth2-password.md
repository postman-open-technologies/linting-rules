---
openapi-v3-security-scheme-oauth2-password:
  description: Requires the usage of OAuth2 password for security scheme.
  message: Must add OAuth2 password implicit for security scheme.
  recommended: true
  severity: error
  formats:
    - oas3
  type: style
  given: $
  then:
    field: $.components.securitySchemes.[*].flows.password
    function: truthy
...
openapi-v3-security-scheme-oauth2-password:
  description: Requires the usage of OAuth2 password for security scheme.
  message: Must add OAuth2 password implicit for security scheme.
  recommended: true
  severity: error
  formats:
    - oas3
  type: style
  given: $
  then:
    field: $.components.securitySchemes.[*].flows.password
    function: truthy
