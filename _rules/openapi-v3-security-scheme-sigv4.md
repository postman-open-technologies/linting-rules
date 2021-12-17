---
openapi-v3-security-scheme-sigv4:
  description: Requires the usage of Sigv4 for security scheme.
  message: Must add Sigv4 for security scheme.
  severity: error
  given: $..components.securitySchemes
  then:
    field: sigv4
    function: truthy
...
openapi-v3-security-scheme-sigv4:
  description: Requires the usage of Sigv4 for security scheme.
  message: Must add Sigv4 for security scheme.
  severity: error
  given: $..components.securitySchemes
  then:
    field: sigv4
    function: truthy
