---
response-post-201-media-type:
  severity: error
  description: POST responses should have a JSON body.
  given: $paths.post.responses.201.content
  then:
    field: "application/json"
    function: truthy
  x-status: draft
  x-tags:
      - Responses       
...
response-post-201-media-type:
  severity: error
  description: POST responses should have a JSON body.
  given: $paths.post.responses.201.content
  then:
    field: "application/json"
    function: truthy
  x-status: draft
  x-tags:
      - Responses  