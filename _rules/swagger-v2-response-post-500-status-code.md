---
swagger-v2-response-post-500-status-code:
  description: Ensures POST operations have a 500 status code response.
  message: A POST operation should have a 500 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas2
  given: $.paths[*].post.responses
  then:
    field: '500'
    function: truthy
...
swagger-v2-response-post-500-status-code:
  description: Ensures POST operations have a 500 status code response.
  message: A POST operation should have a 500 status code for the response.
  severity: warn
  formats:
    - oas2
    - oas2
  given: $.paths[*].post.responses
  then:
    field: '500'
    function: truthy
