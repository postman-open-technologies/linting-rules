---
openapi-v3-response-patch-204-problem-json-media-type:
  description: >-
    Ensuring PATCH operations have an application/problem+json media type for
    500 responses.
  message: >-
    A PATCH operation should have an application/problem+json media type for 500
    response.
  severity: error
  given: $paths.patch.responses.500.content
  then:
    field: application/problem+json
    function: truthy
...
openapi-v3-response-patch-204-problem-json-media-type:
  description: >-
    Ensuring PATCH operations have an application/problem+json media type for
    500 responses.
  message: >-
    A PATCH operation should have an application/problem+json media type for 500
    response.
  severity: error
  given: $paths.patch.responses.500.content
  then:
    field: application/problem+json
    function: truthy
