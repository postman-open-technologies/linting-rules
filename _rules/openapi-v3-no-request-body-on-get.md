---
openapi-v3-no-request-body-on-get:
  description: Ensures that GET methods do not have request bodies.
  message: Your GET methods should not have request bodies.
  given: $.paths.*.get
  recommended: true
  severity: error
  then:
    field: requestBody
    function: falsy
...
openapi-v3-no-request-body-on-get:
  description: Ensures that GET methods do not have request bodies.
  message: Your GET methods should not have request bodies.
  given: $.paths.*.get
  recommended: true
  severity: error
  then:
    field: requestBody
    function: falsy
