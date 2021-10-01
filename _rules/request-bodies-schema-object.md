---
request-bodies-schema-object:
  message: Top-level data structure must be an object
  description: MUST always return JSON objects as top-level data structures
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#110
  severity: error
  given: $.paths.*.*[requestBody]..content..schema
  then:
    function: is-object-schema
...
request-bodies-schema-object:
  message: Top-level data structure must be an object
  description: MUST always return JSON objects as top-level data structures
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#110
  severity: error
  given: $.paths.*.*[requestBody]..content..schema
  then:
    function: is-object-schema