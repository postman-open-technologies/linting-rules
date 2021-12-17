---
openapi-v3-request-body-on-patch:
  description: Ensures that PATCH methods have request bodies.
  message: Your PATCH methods should have request bodies.
  given: $.paths.*.patch
  recommended: true
  severity: error
  then:
    field: requestBody
    function: truthy
...
openapi-v3-request-body-on-patch:
  description: Ensures that PATCH methods have request bodies.
  message: Your PATCH methods should have request bodies.
  given: $.paths.*.patch
  recommended: true
  severity: error
  then:
    field: requestBody
    function: truthy
