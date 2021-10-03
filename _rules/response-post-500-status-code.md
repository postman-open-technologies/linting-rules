---
response-post-500-status-code:
  description: A post operation should have a 500 response.
  message: A POST operation should have a 500 response.
  severity: warn
  formats:
  - oas2
  - oas3
  given: $.paths[*].post.responses
  then:
    field: "500"
    function: truthy
  x-status: validated
  x-tags:
      - Methods
      - Status Codes       
...
response-post-500-status-code:
  description: A post operation should have a 500 response.
  message: A POST operation should have a 500 response.
  severity: warn
  formats:
  - oas2
  - oas3
  given: $.paths[*].post.responses
  then:
    field: "500"
    function: truthy
  x-status: validated
  x-tags:
      - Methods
      - Status Codes  