---
response-post-500-media-type:
  severity: error
  description: POST responses should have a 500 with Problem JSON media type.
  given: $paths.post.responses.500.content
  then:
    field: "application/problem+json"
    function: truthy
  x-status: draft
  x-tags:
      - Responses       
...
response-post-500-media-type:
  severity: error
  description: POST responses should have a 500 with Problem JSON media type.
  given: $paths.post.responses.500.content
  then:
    field: "application/problem+json"
    function: truthy
  x-status: draft
  x-tags:
      - Responses      