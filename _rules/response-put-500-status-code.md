---
response-put-500-status-code:
  description: A put operation should have a 500 response.
  message: A PUT operation should have a 500 response.
  severity: warn
  formats:
  - oas2
  - oas3
  given: $.paths[*].put.responses
  then:
    field: "500"
    function: truthy
  x-status: validated
  x-tags:
      - Methods
      - Status Codes       
...
response-put-500-status-code:
  description: A put operation should have a 500 response.
  message: A PUT operation should have a 500 response.
  severity: warn
  formats:
  - oas2
  - oas3
  given: $.paths[*].put.responses
  then:
    field: "500"
    function: truthy
  x-status: validated
  x-tags:
      - Methods
      - Status Codes 