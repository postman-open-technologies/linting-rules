---
openapi-v3-request-body-examples-components:
  description: >-
    Check request bodies examples to ensure that they only have references to
    components.
  message: Request bodies examples should only reference components.
  severity: error
  resolved: false
  given:
    - $..requestBody.content..*.examples.$ref
  then:
    function: pattern
    functionOptions:
      match: '#/components/'
...
openapi-v3-request-body-examples-components:
  description: >-
    Check request bodies examples to ensure that they only have references to
    components.
  message: Request bodies examples should only reference components.
  severity: error
  resolved: false
  given:
    - $..requestBody.content..*.examples.$ref
  then:
    function: pattern
    functionOptions:
      match: '#/components/'
