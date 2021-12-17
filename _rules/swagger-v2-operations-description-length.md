---
swagger-v2-operations-description-length:
  description: Ensures that the description for operations are not too long.
  message: Your operation descriptions should not be more than 250 characters.
  given: $.paths.*[get,post,patch,put,delete]
  recommended: true
  then:
    - field: description
      function: length
      functionOptions:
        max: 250
  type: style
...
swagger-v2-operations-description-length:
  description: Ensures that the description for operations are not too long.
  message: Your operation descriptions should not be more than 250 characters.
  given: $.paths.*[get,post,patch,put,delete]
  recommended: true
  then:
    - field: description
      function: length
      functionOptions:
        max: 250
  type: style
