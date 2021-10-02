---
response-delete-200-status-code:
  description: A delete operation should have a 200 response.
  message: A delete operation should have a 200 response.
  severity: warn
  formats:
  - oas2
  - oas3
  given: $.paths[*].delete.responses
  then:
    field: "200"
    function: truthy
  x-status: draft
  x-tags:
      - Tag        
...
response-delete-200-status-code:
  description: A delete operation should have a 200 response.
  message: A delete operation should have a 200 response.
  severity: warn
  formats:
  - oas2
  - oas3d
  given: $.paths[*].delete.responses
  then:
    field: "200"
    function: truthy
  x-status: draft
  x-tags:
      - Tag        