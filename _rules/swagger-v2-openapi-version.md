---
swagger-v2-openapi-version:
  description: Ensuring that a specific version of Swagger is being used.
  message: You do not have the right version of Swagger.
  severity: error
  given: $
  then:
    field: swagger
    function: pattern
    functionOptions:
      match: 2
...
swagger-v2-openapi-version:
  description: Ensuring that a specific version of Swagger is being used.
  message: You do not have the right version of Swagger.
  severity: error
  given: $
  then:
    field: swagger
    function: pattern
    functionOptions:
      match: 2
