---
components-security-schema-sigv4:
  description: Please provide a sigv4 for securitySchemes.
  severity: error
  given: $..components.securitySchemes
  then:
    field: sigv4
    function: truthy
  x-status: draft
  x-tags:
    - Tag    
...
components-security-schema-sigv4:
  description: Please provide a sigv4 for securitySchemes.
  severity: error
  given: $..components.securitySchemes
  then:
    field: sigv4
    function: truthy
  x-status: draft
  x-tags:
    - Tag    