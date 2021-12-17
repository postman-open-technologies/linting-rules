---
openapi-v3-response-put-204-no-body:
  description: Ensures PUT operations do not have a response body.
  message: A PUT operation should not have a response body.
  severity: error
  given: $paths.put.responses.204
  then:
    field: content
    function: falsy
...
openapi-v3-response-put-204-no-body:
  description: Ensures PUT operations do not have a response body.
  message: A PUT operation should not have a response body.
  severity: error
  given: $paths.put.responses.204
  then:
    field: content
    function: falsy
