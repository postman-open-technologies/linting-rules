---
openapi-v3-response-post-201-status-code:
  description: Ensures POST operations have a 201 status code response.
  message: A POST operation should have a 201 status code for the response.
  severity: warn
  formats:
    - oas3
  given: $.paths[*].post.responses
  then:
    field: '201'
    function: truthy
...
openapi-v3-response-post-201-status-code:
  description: Ensures POST operations have a 201 status code response.
  message: A POST operation should have a 201 status code for the response.
  severity: warn
  formats:
    - oas3
  given: $.paths[*].post.responses
  then:
    field: '201'
    function: truthy
