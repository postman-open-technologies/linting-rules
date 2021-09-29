---
message: Path with trailing slash is not allowed
description: MUST use normalized paths without empty path segments and trailing slashes
  [136]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#136
severity: error
given: $.paths.*~
then:
  function: pattern
  functionOptions:
    notMatch: /$
...
description: MUST use normalized paths without empty path segments and trailing slashes
  [136]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#136
severity: error
given: $.paths.*~
then:
  function: pattern
  functionOptions:
    notMatch: /$