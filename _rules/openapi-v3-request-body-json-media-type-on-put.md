---
openapi-v3-request-body-json-media-type-on-put:
  description: Ensures that PUT methods have request bodies.
  message: Your PUT methods should have request bodies.
  given: $.paths.*.put[requestBody].content
  recommended: true
  severity: error
  then:
    field: application/json
    function: truthy
...
openapi-v3-request-body-json-media-type-on-put:
  description: Ensures that PUT methods have request bodies.
  message: Your PUT methods should have request bodies.
  given: $.paths.*.put[requestBody].content
  recommended: true
  severity: error
  then:
    field: application/json
    function: truthy
