---
message: '{{error}}'
description: MUST provide API identifiers [215]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#215
severity: error
given: $.info.x-api-id
then:
  function: schema
  functionOptions:
    schema:
      type: string
      pattern: ^[a-z0-9][a-z0-9-:.]{6,62}[a-z0-9]$
...message: '{{error}}'
description: MUST provide API identifiers [215]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#215
severity: error
given: $.info.x-api-id
then:
  function: schema
  functionOptions:
    schema:
      type: string
      pattern: ^[a-z0-9][a-z0-9-:.]{6,62}[a-z0-9]$