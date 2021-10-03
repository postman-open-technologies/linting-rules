---
response-put-204-status-code:
  description: A put operation should have a 204 response.
  message: A delete operation should have a 204 response.
  severity: warn
  formats:
  - oas2
  - oas3
  given: $.paths[*].delete.responses
  then:
    field: "204"
    function: truthy
  x-status: valiated
  x-tags:
      - Methods
      - Status Codes        
...
response-put-204-status-code:
  description: A put operation should have a 204 response.
  message: A delete operation should have a 204 response.
  severity: warn
  formats:
  - oas2
  - oas3
  given: $.paths[*].delete.responses
  then:
    field: "204"
    function: truthy
  x-status: valiated
  x-tags:
      - Methods
      - Status Codes        