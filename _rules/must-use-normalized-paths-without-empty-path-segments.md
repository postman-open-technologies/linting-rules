---
message: Empty path segments are not allowed
description: MUST use normalized paths without empty path segments and trailing slashes
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#136
severity: error
given: $.paths.*~
then:
  function: pattern
  functionOptions:
    notMatch: //
...
message: Empty path segments are not allowed
description: MUST use normalized paths without empty path segments and trailing slashes
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#136
severity: error
given: $.paths.*~
then:
  function: pattern
  functionOptions:
    notMatch: //