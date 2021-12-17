---
openapi-v3-response-put-204-problem-json-media-type:
  description: >-
    Ensuring PUT operations have an application/problem+json media type for 500
    responses.
  message: >-
    A PUT operation should have an application/problem+json media type for 500
    response.
  severity: error
  given: $paths.put.responses.500.content
  then:
    field: application/problem+json
    function: truthy
...
openapi-v3-response-put-204-problem-json-media-type:
  description: >-
    Ensuring PUT operations have an application/problem+json media type for 500
    responses.
  message: >-
    A PUT operation should have an application/problem+json media type for 500
    response.
  severity: error
  given: $paths.put.responses.500.content
  then:
    field: application/problem+json
    function: truthy
