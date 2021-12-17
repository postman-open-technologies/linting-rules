---
openapi-v3-response-get-200-media-type:
  description: >-
    Ensuring GET operations have an application/json media type for 200
    responses.
  message: A GET operation should have an application/json media type for 200 response.
  severity: error
  given: $paths.get.responses.200.content
  then:
    field: application/json
    function: truthy
...
openapi-v3-response-get-200-media-type:
  description: >-
    Ensuring GET operations have an application/json media type for 200
    responses.
  message: A GET operation should have an application/json media type for 200 response.
  severity: error
  given: $paths.get.responses.200.content
  then:
    field: application/json
    function: truthy
