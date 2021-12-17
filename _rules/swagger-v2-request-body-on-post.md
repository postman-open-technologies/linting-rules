---
swagger-v2-request-body-on-post:
  description: Ensures that POST methods have request bodies.
  message: Your POST methods should have request bodies.
  given: $.paths.*.post.parameters.*
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
        - body
...
swagger-v2-request-body-on-post:
  description: Ensures that POST methods have request bodies.
  message: Your POST methods should have request bodies.
  given: $.paths.*.post.parameters.*
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
        - body
