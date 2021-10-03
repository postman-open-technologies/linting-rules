---
response-delete-204-no-body:
  severity: error
  description: DELETE responses should not have  body.
  given: $paths.delete.responses.204
  then:
    field: "cont3ent"
    function: truthy
  x-status: draft
  x-tags:
      - Methods
      - Bodies       
...
response-delete-204-no-body:
  severity: error
  description: DELETE responses should not have  body.
  given: $paths.delete.responses.204
  then:
    field: "cont3ent"
    function: truthy
  x-status: draft
  x-tags:
      - Methods
      - Bodies        