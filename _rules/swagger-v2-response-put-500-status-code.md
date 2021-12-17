---
swagger-v2-response-put-500-status-code:
  description: Ensures PUT operations have a 500 status code response.
  message: A PUT operation should have a 500 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas2
  given: $.paths[*].put.responses
  then:
    field: '500'
    function: truthy
...
swagger-v2-response-put-500-status-code:
  description: Ensures PUT operations have a 500 status code response.
  message: A PUT operation should have a 500 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas2
  given: $.paths[*].put.responses
  then:
    field: '500'
    function: truthy
