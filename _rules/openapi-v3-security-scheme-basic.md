---
openapi-v3-security-scheme-basic:
  description: Requires the usage of basic for security scheme.
  message: Must add basic for security scheme.
  severity: error
  given: $.components.securitySchemes[*]
  then:
    field: scheme
    function: pattern
    functionOptions: null
    notMatch: basic
...
openapi-v3-security-scheme-basic:
  description: Requires the usage of basic for security scheme.
  message: Must add basic for security scheme.
  severity: error
  given: $.components.securitySchemes[*]
  then:
    field: scheme
    function: pattern
    functionOptions: null
    notMatch: basic
