---
description: The API must contain the security mechanism OAuth2
message: The API must contain the security mechanism OAuth2
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
message: The API must contain the security mechanism OAuth2
recommended: true
severity: error
formats:
- oas3
type: style
given: $
then:
  field: $.components.securitySchemes.[*].type
  function: truthy