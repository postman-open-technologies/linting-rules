---
swagger-v2-security-basic:
  description: Requires the usage of an basic for security.
  message: Must add security definition object with type of basic
  severity: error
  given: $.security.*
  then:
    field: type
    function: enumeration
    functionOptions:
      values:
        - basic
...
swagger-v2-security-basic:
  description: Requires the usage of an basic for security.
  message: Must add security definition object with type of basic
  severity: error
  given: $.security.*
  then:
    field: type
    function: enumeration
    functionOptions:
      values:
        - basic
