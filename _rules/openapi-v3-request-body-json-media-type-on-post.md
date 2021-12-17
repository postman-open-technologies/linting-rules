---
openapi-v3-request-body-json-media-type-on-post:
  description: Ensures that POST methods have request bodies.
  message: Your POST methods should have request bodies.
  given: $.paths.*.post[requestBody].content
  recommended: true
  severity: error
  then:
    field: application/json
    function: truthy
...
openapi-v3-request-body-json-media-type-on-post:
  description: Ensures that POST methods have request bodies.
  message: Your POST methods should have request bodies.
  given: $.paths.*.post[requestBody].content
  recommended: true
  severity: error
  then:
    field: application/json
    function: truthy
