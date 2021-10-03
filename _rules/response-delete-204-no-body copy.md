---
response-put-204-no-body:
  severity: error
  description: PUT responses should not have  body.
  given: $paths.put.responses
  then:
    field: "204"
    function: truthy
  x-status: draft
  x-tags:
      - Methods
      - Bodies       
...
response-put-204-no-body:
  severity: error
  description: PUT responses should not have  body.
  given: $paths.put.responses
  then:
    field: "204"
    function: truthy
  x-status: draft
  x-tags:
      - Methods
      - Bodies       