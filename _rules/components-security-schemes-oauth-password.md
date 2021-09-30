---
components-security-schemes-oauth-password:
  description: The API must contain the security mechanism OAuth2 password
  message: The API must contain the security mechanism  OAuth2 password
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
components-security-schemes-oauth-password:
  description: The API must contain the security mechanism OAuth2 password
  message: The API must contain the security mechanism  OAuth2 password
  recommended: true
  severity: error
  formats:
  - oas3
  type: style
  given: $
  then:
    field: $.components.securitySchemes.[*].flows.password
    function: truthy