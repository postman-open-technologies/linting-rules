---
swagger-v2-no-request-body-on-get:
  description: Ensures that GET methods do not have request bodies.
  message: Your GET methods should not have request bodies.
  given: $.paths.*.get.parameters.*
  recommended: true
  severity: error
  then:
    field: in
    function: enumeration
    functionOptions:
      values:
        - query
        - header
        - path
...
swagger-v2-no-request-body-on-get:
  description: Ensures that GET methods do not have request bodies.
  message: Your GET methods should not have request bodies.
  given: $.paths.*.get.parameters.*
  recommended: true
  severity: error
  then:
    field: in
    function: enumeration
    functionOptions:
      values:
        - query
        - header
        - path
