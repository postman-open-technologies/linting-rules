---
response-post-201-status-code:
  description: A post operation should have a 201 response.
  message: A POST operation should have a 201 response.
  severity: warn
  formats:
  - oas3
  given: $.paths[*].post.responses
  then:
    field: "201"
    function: truthy
  x-status: validated
  x-tags:
      - Methods
      - Status Codes       
...
response-post-201-status-code:
  description: A post operation should have a 201 response.
  message: A POST operation should have a 201 response.
  severity: warn
  formats:
  - oas3
  given: $.paths[*].post.responses
  then:
    field: "201"
    function: truthy
  x-status: validated
  x-tags:
      - Methods
      - Status Codes 