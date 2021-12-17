---
swagger-v2-security-oauth2:
  description: Requires the usage of an OAuth 2.0 for security.
  message: Must add security definition object with type of oauth2
  severity: error
  given: $.security.*
  then:
    field: type
    function: enumeration
    functionOptions:
      values:
        - oauth2
...
swagger-v2-security-oauth2:
  description: Requires the usage of an OAuth 2.0 for security.
  message: Must add security definition object with type of oauth2
  severity: error
  given: $.security.*
  then:
    field: type
    function: enumeration
    functionOptions:
      values:
        - oauth2
