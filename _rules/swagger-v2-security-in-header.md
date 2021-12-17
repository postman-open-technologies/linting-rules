---
swagger-v2-security-in-header:
  description: Requires the usage of header for security.
  message: Must add header to in property for security object
  severity: error
  given: $.security.*
  then:
    field: in
    function: enumeration
    functionOptions:
      values:
        - header
...
swagger-v2-security-in-header:
  description: Requires the usage of header for security.
  message: Must add header to in property for security object
  severity: error
  given: $.security.*
  then:
    field: in
    function: enumeration
    functionOptions:
      values:
        - header
