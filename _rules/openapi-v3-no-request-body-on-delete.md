---
openapi-v3-no-request-body-on-delete:
  description: Ensures that DELETE methods do not have request bodies.
  message: Your DELETE methods should not have request bodies.
  given: $.paths.*.delete
  recommended: true
  severity: error
  then:
    field: requestBody
    function: falsy
...
openapi-v3-no-request-body-on-delete:
  description: Ensures that DELETE methods do not have request bodies.
  message: Your DELETE methods should not have request bodies.
  given: $.paths.*.delete
  recommended: true
  severity: error
  then:
    field: requestBody
    function: falsy
