---
openapi-v3-response-get-500-status-code:
  description: Ensures GET operations have a 500 status code response.
  message: A GET operation should have a 500 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas3
  given: $.paths[*].get.responses
  then:
    field: '500'
    function: truthy
...
openapi-v3-response-get-500-status-code:
  description: Ensures GET operations have a 500 status code response.
  message: A GET operation should have a 500 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas3
  given: $.paths[*].get.responses
  then:
    field: '500'
    function: truthy
