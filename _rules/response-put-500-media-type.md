---
response-put-500-media-type:
  severity: error
  description: PUT responses should have a 500 with Problem JSON media type.
  given: $paths.put.responses.500.content
  then:
    field: "application/problem+json"
    function: truthy
  x-status: draft
  x-tags:
      - Responses       
...
response-put-500-media-type:
  severity: error
  description: PUT responses should have a 500 with Problem JSON media type.
  given: $paths.put.responses.500.content
  then:
    field: "application/problem+json"
    function: truthy
  x-status: draft
  x-tags:
      - Responses      