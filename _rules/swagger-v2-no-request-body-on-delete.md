---
swagger-v2-no-request-body-on-delete:
  description: Ensures that DELETE methods do not have request bodies.
  message: Your DELETE methods should not have request bodies.
  given: $.paths.*.delete
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
swagger-v2-no-request-body-on-delete:
  description: Ensures that DELETE methods do not have request bodies.
  message: Your DELETE methods should not have request bodies.
  given: $.paths.*.delete
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
