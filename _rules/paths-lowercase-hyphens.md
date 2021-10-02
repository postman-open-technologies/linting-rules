---
paths-lowercase-hyphens:
  message: Path segments have to be lowercase separate words with hyphens
  description: MUST use lowercase separate words with hyphens for path segments
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      match: ^(([\/a-z][a-z0-9\-\/]*)?({[^}]*})?)+$
  x-status: validated
  x-tags:
      - Paths        
...
paths-lowercase-hyphens:
  message: Path segments have to be lowercase separate words with hyphens
  description: MUST use lowercase separate words with hyphens for path segments [129]
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#129
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      match: ^(([\/a-z][a-z0-9\-\/]*)?({[^}]*})?)+$
  x-status: validated
  x-tags:
      - Paths       