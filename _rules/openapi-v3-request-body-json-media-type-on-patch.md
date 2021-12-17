---
openapi-v3-request-body-json-media-type-on-patch:
  description: Ensures that PATCH methods have request bodies.
  message: Your PATCH methods should have request bodies.
  given: $.paths.*.patch[requestBody].content
  recommended: true
  severity: error
  then:
    field: application/json
    function: truthy
...
openapi-v3-request-body-json-media-type-on-patch:
  description: Ensures that PATCH methods have request bodies.
  message: Your PATCH methods should have request bodies.
  given: $.paths.*.patch[requestBody].content
  recommended: true
  severity: error
  then:
    field: application/json
    function: truthy
