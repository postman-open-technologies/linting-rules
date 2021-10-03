---
paths-limit-number-of:
  message: '{{error}}'
  description: SHOULD limit number of resource types [146]
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#146
  severity: warn
  given: $.paths
  then:
    function: count-resource-types
    functionOptions:
      max: 1
  x-status: draft
  x-tags:
      - Tag            
...
paths-limit-number-of:
  message: '{{error}}'
  description: SHOULD limit number of resource types [146]
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#146
  severity: warn
  given: $.paths
  then:
    function: count-resource-types
    functionOptions:
      max: 1
  x-status: draft
  x-tags:
      - Tag        