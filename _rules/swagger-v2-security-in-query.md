---
swagger-v2-security-in-query:
  description: Requires the usage of query parameter for security.
  message: Must add query parameter to in property for security object
  severity: error
  given: $.security.*
  then:
    field: in
    function: enumeration
    functionOptions:
      values:
        - query
...
swagger-v2-security-in-query:
  description: Requires the usage of query parameter for security.
  message: Must add query parameter to in property for security object
  severity: error
  given: $.security.*
  then:
    field: in
    function: enumeration
    functionOptions:
      values:
        - query
