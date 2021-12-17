---
openapi-v3-response-delete-204-no-body:
  description: Ensures DELETE operations do not have a response body.
  message: A DELETE operation should not have a response body.
  severity: error
  given: $paths.delete.responses.204
  then:
    field: content
    function: falsy
...
openapi-v3-response-delete-204-no-body:
  description: Ensures DELETE operations do not have a response body.
  message: A DELETE operation should not have a response body.
  severity: error
  given: $paths.delete.responses.204
  then:
    field: content
    function: falsy
