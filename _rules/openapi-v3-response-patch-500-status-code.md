---
openapi-v3-response-patch-500-status-code:
  description: Ensures PATCH operations have a 500 status code response.
  message: A PATCH operation should have a 500 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas3
  given: $.paths[*].patch.responses
  then:
    field: '500'
    function: truthy
...
openapi-v3-response-patch-500-status-code:
  description: Ensures PATCH operations have a 500 status code response.
  message: A PATCH operation should have a 500 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas3
  given: $.paths[*].patch.responses
  then:
    field: '500'
    function: truthy
