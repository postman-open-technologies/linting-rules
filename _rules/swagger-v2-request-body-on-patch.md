---
swagger-v2-request-body-on-patch:
  description: Ensures that PATCH methods have request bodies.
  message: Your PATCH methods should have request bodies.
  given: $.paths.*.patch
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
swagger-v2-request-body-on-patch:
  description: Ensures that PATCH methods have request bodies.
  message: Your PATCH methods should have request bodies.
  given: $.paths.*.patch
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
