---
openapi-v3-response-get-200-status-code:
  description: Ensures GET operations have a 200 status code response.
  message: A GET operation should have a 200 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas3
  given: $.paths[*].get.responses
  then:
    field: '200'
    function: truthy
...
openapi-v3-response-get-200-status-code:
  description: Ensures GET operations have a 200 status code response.
  message: A GET operation should have a 200 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas3
  given: $.paths[*].get.responses
  then:
    field: '200'
    function: truthy
