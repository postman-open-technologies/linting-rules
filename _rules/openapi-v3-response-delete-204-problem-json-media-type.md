---
openapi-v3-response-delete-204-problem-json-media-type:
  description: >-
    Ensuring DELETE operations have an application/problem+json media type for
    500 responses.
  message: >-
    A DELETE operation should have an application/problem+json media type for
    500 response.
  severity: error
  given: $paths.delete.responses.500.content
  then:
    field: application/problem+json
    function: truthy
...
openapi-v3-response-delete-204-problem-json-media-type:
  description: >-
    Ensuring DELETE operations have an application/problem+json media type for
    500 responses.
  message: >-
    A DELETE operation should have an application/problem+json media type for
    500 response.
  severity: error
  given: $paths.delete.responses.500.content
  then:
    field: application/problem+json
    function: truthy
