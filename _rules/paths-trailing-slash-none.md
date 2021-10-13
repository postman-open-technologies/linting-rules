---
paths-trailing-slash-none:
  message: Path with trailing slash is not allowed
  description: All paths must not end with a trailing slash.
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#136
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: /$
  x-status: validated
  x-tags:
      - Tag        
...
paths-trailing-slash-none:
  message: Path with trailing slash is not allowed
  description: All paths must not end with a trailing slash.
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#136
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: /$
  x-status: validated
  x-tags:
      - Tag        