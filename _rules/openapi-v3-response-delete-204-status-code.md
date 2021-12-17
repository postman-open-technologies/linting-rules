---
openapi-v3-response-delete-204-status-code:
  description: Ensures DELETE operations have a 204 status code response.
  message: A DELETE operation should have a 204 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas3
  given: $.paths[*].delete.responses
  then:
    field: '204'
    function: truthy
...
openapi-v3-response-delete-204-status-code:
  description: Ensures DELETE operations have a 204 status code response.
  message: A DELETE operation should have a 204 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas3
  given: $.paths[*].delete.responses
  then:
    field: '204'
    function: truthy
