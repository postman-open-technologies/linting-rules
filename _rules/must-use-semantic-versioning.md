---
message: '{{error}}'
description: MUST use semantic versioning [116]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#116
severity: error
given: $.info.version
then:
  function: schema
  functionOptions:
    schema:
      type: string
      pattern: ^[0-9]+\.[0-9]+\.[0-9]+(-[0-9a-zA-Z-]+(\.[0-9a-zA-Z-]+)*)?$
...message: '{{error}}'
description: MUST use semantic versioning [116]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#116
severity: error
given: $.info.version
then:
  function: schema
  functionOptions:
    schema:
      type: string
      pattern: ^[0-9]+\.[0-9]+\.[0-9]+(-[0-9a-zA-Z-]+(\.[0-9a-zA-Z-]+)*)?$