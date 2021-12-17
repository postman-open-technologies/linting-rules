---
openapi-v3-security-scheme-api-key:
  description: Requires the usage of API key for security scheme.
  message: Must add API key for security scheme.
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
        match: ^X-api-key$
...
openapi-v3-security-scheme-api-key:
  description: Requires the usage of API key for security scheme.
  message: Must add API key for security scheme.
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
        match: ^X-api-key$
