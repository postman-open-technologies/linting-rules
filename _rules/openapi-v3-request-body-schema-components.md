---
openapi-v3-request-body-schema-components:
  description: >-
    Check request body schena to ensure that they only have references to
    components.
  message: Request body schema should only reference components.
  severity: error
  resolved: false
  given:
    - $..requestBody.content..*.schema.$ref
  then:
    function: pattern
    functionOptions:
      match: '#/components/'
...
openapi-v3-request-body-schema-components:
  description: >-
    Check request body schena to ensure that they only have references to
    components.
  message: Request body schema should only reference components.
  severity: error
  resolved: false
  given:
    - $..requestBody.content..*.schema.$ref
  then:
    function: pattern
    functionOptions:
      match: '#/components/'
