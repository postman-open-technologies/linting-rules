---
openapi-v3-response-patch-204-status-code:
  description: Ensures PATCH operations have a 204 status code response.
  message: A PATCH operation should have a 204 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas3
  given: $.paths[*].delete.responses
  then:
    field: '204'
    function: truthy
...
openapi-v3-response-patch-204-status-code:
  description: Ensures PATCH operations have a 204 status code response.
  message: A PATCH operation should have a 204 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas3
  given: $.paths[*].delete.responses
  then:
    field: '204'
    function: truthy
