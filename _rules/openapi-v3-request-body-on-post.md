---
openapi-v3-request-body-on-post:
  description: Ensures that POST methods have request bodies.
  message: Your POST methods should have request bodies.
  given: $.paths.*.post
  recommended: true
  severity: error
  then:
    field: requestBody
    function: truthy
...
openapi-v3-request-body-on-post:
  description: Ensures that POST methods have request bodies.
  message: Your POST methods should have request bodies.
  given: $.paths.*.post
  recommended: true
  severity: error
  then:
    field: requestBody
    function: truthy
