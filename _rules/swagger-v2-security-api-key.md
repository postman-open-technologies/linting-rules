---
swagger-v2-security-api-key:
  description: Requires the usage of an API key for security.
  message: Must add security definition object with type of apiKey
  severity: error
  given: $.security.*
  then:
    field: type
    function: enumeration
    functionOptions:
      values:
        - apiKey
...
swagger-v2-security-api-key:
  description: Requires the usage of an API key for security.
  message: Must add security definition object with type of apiKey
  severity: error
  given: $.security.*
  then:
    field: type
    function: enumeration
    functionOptions:
      values:
        - apiKey
