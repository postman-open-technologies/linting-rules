---
response-delete-500-media-type:
  severity: error
  description: DELETE responses should have a 500 with Problem JSON media type.
  given: $paths.delete.responses.500.content
  then:
    field: "application/problem+json"
    function: truthy
  x-status: draft
  x-tags:
      - Responses       
...
response-delete-500-media-type:
  severity: error
  description: DELETE responses should have a 500 with Problem JSON media type.
  given: $paths.delete.responses.500.content
  then:
    field: "application/problem+json"
    function: truthy
  x-status: draft
  x-tags:
      - Responses   