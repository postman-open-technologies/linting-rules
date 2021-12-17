---
swagger-v2-security-applied-to-operations:
  description: Requires security to be applied to all operations.
  message: Each operation must have a security property.
  severity: error
  given: $.paths.*.*
  then:
    field: security
    function: truthy
...
swagger-v2-security-applied-to-operations:
  description: Requires security to be applied to all operations.
  message: Each operation must have a security property.
  severity: error
  given: $.paths.*.*
  then:
    field: security
    function: truthy
