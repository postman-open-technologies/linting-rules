---
message: '{{error}}'
description: SHOULD limit number of resource types [146]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#146
severity: warn
given: $.paths
then:
  function: count-resource-types
  functionOptions:
    max: 8
...
description: SHOULD limit number of resource types [146]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#146
severity: warn
given: $.paths
then:
  function: count-resource-types
  functionOptions:
    max: 8