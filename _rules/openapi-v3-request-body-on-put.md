---
openapi-v3-request-body-on-put:
  description: Ensures that PUT methods have request bodies.
  message: Your PUT methods should have request bodies.
  given: $.paths.*.put
  recommended: true
  severity: error
  then:
    field: requestBody
    function: truthy
...
openapi-v3-request-body-on-put:
  description: Ensures that PUT methods have request bodies.
  message: Your PUT methods should have request bodies.
  given: $.paths.*.put
  recommended: true
  severity: error
  then:
    field: requestBody
    function: truthy
