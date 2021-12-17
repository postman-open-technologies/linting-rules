---
openapi-v3-operations-summary:
  description: Ensures that each of the operations for an API have a summary.
  message: All of your operations need summaries.
  severity: error
  given: $.paths.*[get,post,patch,put,delete]
  then:
    - field: summary
      function: truthy
...
openapi-v3-operations-summary:
  description: Ensures that each of the operations for an API have a summary.
  message: All of your operations need summaries.
  severity: error
  given: $.paths.*[get,post,patch,put,delete]
  then:
    - field: summary
      function: truthy
