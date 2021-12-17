---
openapi-v3-response-get-500-problem-json-media-type:
  description: >-
    Ensuring GET operations have an application/problem+json media type for 500
    responses.
  message: >-
    A GET operation should have an application/problem+json media type for 500
    response.
  severity: error
  given: $paths.get.responses.500.content
  then:
    field: application/problem+json
    function: truthy
...
openapi-v3-response-get-500-problem-json-media-type:
  description: >-
    Ensuring GET operations have an application/problem+json media type for 500
    responses.
  message: >-
    A GET operation should have an application/problem+json media type for 500
    response.
  severity: error
  given: $paths.get.responses.500.content
  then:
    field: application/problem+json
    function: truthy
