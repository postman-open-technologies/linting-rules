---
openapi-v3-security-scheme-access-token:
  description: Requires the usage of access token for security scheme.
  message: Must add access token for security scheme.
  given: $.components.securitySchemes[Oidc.AccessToken]
  severity: error
  then:
    field: type
    function: pattern
    functionOptions:
      match: ^openIdConnect$
...
openapi-v3-security-scheme-access-token:
  description: Requires the usage of access token for security scheme.
  message: Must add access token for security scheme.
  given: $.components.securitySchemes[Oidc.AccessToken]
  severity: error
  then:
    field: type
    function: pattern
    functionOptions:
      match: ^openIdConnect$
