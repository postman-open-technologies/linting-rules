---
message: Error response must be application/problem+json
description: MUST support problem JSON [176]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#176
severity: error
given: $.paths.*.*.responses[?(@property.match(/^(4|5)/))]
then:
  field: content.application/problem+json
  function: truthy
...message: Error response must be application/problem+json
description: MUST support problem JSON [176]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#176
severity: error
given: $.paths.*.*.responses[?(@property.match(/^(4|5)/))]
then:
  field: content.application/problem+json
  function: truthy