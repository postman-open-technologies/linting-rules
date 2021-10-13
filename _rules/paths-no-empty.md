---
paths-no-empty:
  message: Empty path segments are not allowed
  description: There should be no empty path segments.
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#136
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: //
  x-status: validated
  x-tags:
      - Tag        
...
paths-no-empty:
  message: Empty path segments are not allowed
  description: There should be no empty path segments.
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#136
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: //
  x-status: validated
  x-tags:
      - Tag       