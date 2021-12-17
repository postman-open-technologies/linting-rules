---
openapi-v3-security-scheme-api-secret:
  description: Requires the usage of API secret for security scheme.
  message: Must add API secret for security scheme.
  given: $.components.securitySchemes[Keys.ClientId]
  severity: error
  then:
    - field: type
      function: pattern
      functionOptions:
        match: ^apiKey$
    - field: in
      function: pattern
      functionOptions:
        match: ^header$
    - field: name
      function: pattern
      functionOptions:
        match: ^X-api-secret$
...
openapi-v3-security-scheme-api-secret:
  description: Requires the usage of API secret for security scheme.
  message: Must add API secret for security scheme.
  given: $.components.securitySchemes[Keys.ClientId]
  severity: error
  then:
    - field: type
      function: pattern
      functionOptions:
        match: ^apiKey$
    - field: in
      function: pattern
      functionOptions:
        match: ^header$
    - field: name
      function: pattern
      functionOptions:
        match: ^X-api-secret$
