---
openapi-v3-response-get-500-problem-json-media-type:
  description: >-
    Ensuring POST operations have an application/problem+json media type for 500
    responses.
  message: >-
    A POST operation should have an application/problem+json media type for 500
    response.
  severity: error
  given: $paths.post.responses.500.content
  then:
    field: application/problem+json
    function: truthy
...
openapi-v3-response-get-500-problem-json-media-type:
  description: >-
    Ensuring POST operations have an application/problem+json media type for 500
    responses.
  message: >-
    A POST operation should have an application/problem+json media type for 500
    response.
  severity: error
  given: $paths.post.responses.500.content
  then:
    field: application/problem+json
    function: truthy
