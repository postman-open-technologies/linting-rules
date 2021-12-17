---
swagger-v2-request-body-on-put:
  description: Ensures that PUT methods have request bodies.
  message: Your PUT methods should have request bodies.
  given: $.paths.*.put
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
swagger-v2-request-body-on-put:
  description: Ensures that PUT methods have request bodies.
  message: Your PUT methods should have request bodies.
  given: $.paths.*.put
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
