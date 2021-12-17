---
openapi-v3-operations-summary-length:
  description: Ensures that each of the operations summaries are not too long.
  message: Your operations summaries can't be longer than 50 characters.
  given: $.paths.*[get,post,patch,put,delete]
  recommended: true
  then:
    - field: summary
      function: length
      functionOptions:
        max: 50
  type: style
...
openapi-v3-operations-summary-length:
  description: Ensures that each of the operations summaries are not too long.
  message: Your operations summaries can't be longer than 50 characters.
  given: $.paths.*[get,post,patch,put,delete]
  recommended: true
  then:
    - field: summary
      function: length
      functionOptions:
        max: 50
  type: style
