---
response-delete-204-no-body:
  severity: error
  description: DELETE responses should not have  body.
  given: $paths.delete.responses
  then:
    field: "204"
    function: truthy
  x-status: draft
  x-tags:
      - Methods
      - Bodies       
...
response-delete-204-no-body:
  severity: error
  description: DELETE responses should not have  body.
  given: $paths.delete.responses
  then:
    field: "204"
    function: truthy
  x-status: draft
  x-tags:
      - Methods
      - Bodies        