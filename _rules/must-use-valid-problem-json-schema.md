---
message: '{{error}}'
description: MUST support problem JSON [176]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#176
severity: error
given: $.paths.*.*.responses.*.content.application/problem+json
then:
  field: schema
  function: is-problem-json-schema
...message: '{{error}}'
description: MUST support problem JSON [176]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#176
severity: error
given: $.paths.*.*.responses.*.content.application/problem+json
then:
  field: schema
  function: is-problem-json-schema