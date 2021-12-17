---
openapi-v3-operations-description:
  description: Ensures that each of the operations have a description.
  message: Your operations all need descriptions.
  severity: error
  given: $.paths.*[get,post,patch,put,delete]
  then:
    - field: description
      function: truthy
...
openapi-v3-operations-description:
  description: Ensures that each of the operations have a description.
  message: Your operations all need descriptions.
  severity: error
  given: $.paths.*[get,post,patch,put,delete]
  then:
    - field: description
      function: truthy
