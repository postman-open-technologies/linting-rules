---
openapi-v3-openapi-version:
  description: Ensuring that a specific version of OpenAPI is being used.
  message: You do not have the right version of OpenAPI.
  severity: error
  given: $
  then:
    field: openapi
    function: pattern
    functionOptions:
      match: 3.0.3
...
openapi-v3-openapi-version:
  description: Ensuring that a specific version of OpenAPI is being used.
  message: You do not have the right version of OpenAPI.
  severity: error
  given: $
  then:
    field: openapi
    function: pattern
    functionOptions:
      match: 3.0.3
