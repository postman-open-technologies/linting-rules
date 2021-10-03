---
response-get-200-no-body:
  severity: error
  description: GET responses should not have  body.
  given: $paths.get.responses.200.content
  then:
    field: "application/json"
    function: truthy
  x-status: draft
  x-tags:
      - Responses       
...
response-get-201-no-body:
  severity: error
  description: GET responses should not have  body.
  given: $paths.get.responses.201.content
  then:
    field: "application/json"
    function: truthy
  x-status: draft
  x-tags:
      - Responses        