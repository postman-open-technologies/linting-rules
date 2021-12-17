---
openapi-v3-have-request-body-examples:
  severity: error
  description: Ensures that a example is always present for each request body.
  message: All request bodies should have an example present.
  given: $.paths.*.*.requestBody..[?(@.items)][?(@.type == 'object')]
  formats:
    - oas3
  then:
    - field: example
      function: truthy
...
openapi-v3-have-request-body-examples:
  severity: error
  description: Ensures that a example is always present for each request body.
  message: All request bodies should have an example present.
  given: $.paths.*.*.requestBody..[?(@.items)][?(@.type == 'object')]
  formats:
    - oas3
  then:
    - field: example
      function: truthy
