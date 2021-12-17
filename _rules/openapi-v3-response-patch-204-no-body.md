---
openapi-v3-response-patch-204-no-body:
  description: Ensures PATCH operations do not have a response body.
  message: A PATCH operation should not have a response body.
  severity: error
  given: $paths.patch.responses.204
  then:
    field: content
    function: falsy
...
openapi-v3-response-patch-204-no-body:
  description: Ensures PATCH operations do not have a response body.
  message: A PATCH operation should not have a response body.
  severity: error
  given: $paths.patch.responses.204
  then:
    field: content
    function: falsy
