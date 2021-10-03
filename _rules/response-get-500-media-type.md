---
response-get-500-media-type:
  severity: error
  description: GET responses should have a 500 with Problem JSON media type.
  given: $paths.get.responses.500.content
  then:
    field: "application/problem+json"
    function: truthy
  x-status: draft
  x-tags:
      - Responses       
...
response-get-500-media-type:
  severity: error
  description: GET responses should have a 500 with Problem JSON media type.
  given: $paths.get.responses.500.content
  then:
    field: "application/problem+json"
    function: truthy
  x-status: draft
  x-tags:
      - Responses       