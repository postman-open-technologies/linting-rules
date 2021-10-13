---
paths-trailing-slash:
  message: Path with trailing slash is not allowed
  description: All paths must end with a trailing slash.
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#136
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      match: /$
  x-status: validated
  x-tags:
      - Tag        
...
paths-trailing-slash:
  message: Path with trailing slash is not allowed
  description: All paths must end with a trailing slash.
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#136
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      match: /$
  x-status: validated
  x-tags:
      - Tag        