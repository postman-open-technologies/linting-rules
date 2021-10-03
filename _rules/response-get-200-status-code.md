---
response-get-200-status-code:
  description: A get operation should have a 200 response.
  message: A GET operation should have a 200 response.
  severity: warn
  formats:
  - oas2
  - oas3
  given: $.paths[*].get.responses
  then:
    field: "200"
    function: truthy
  x-status: validated
  x-tags:
      - Methods
      - Status Codes       
...
response-get-204-status-code:
  description: A get operation should have a 204 response.
  message: A GET operation should have a 204 response.
  severity: warn
  formats:
  - oas2
  - oas3
  given: $.paths[*].get.responses
  then:
    field: "200"
    function: truthy
  x-status: validated
  x-tags:
      - Methods
      - Status Codes     