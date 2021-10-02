---
paths-base-api-none:
  message: Path should not start with /api
  description: SHOULD not use /api as base path [135]
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#135
  severity: warn
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: ^/api
...
paths-base-api-none:
  message: Path should not start with /api
  description: SHOULD not use /api as base path [135]
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#135
  severity: warn
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: ^/api