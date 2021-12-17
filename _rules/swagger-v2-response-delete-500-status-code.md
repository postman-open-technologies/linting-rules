---
swagger-v2-response-delete-500-status-code:
  description: Ensures DELETE operations have a 500 status code response.
  message: A DELETE operation should have a 500 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas2
  given: $.paths[*].delete.responses
  then:
    field: '500'
    function: truthy
...
swagger-v2-response-delete-500-status-code:
  description: Ensures DELETE operations have a 500 status code response.
  message: A DELETE operation should have a 500 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas2
  given: $.paths[*].delete.responses
  then:
    field: '500'
    function: truthy
