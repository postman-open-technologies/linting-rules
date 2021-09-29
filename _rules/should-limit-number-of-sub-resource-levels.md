---
message: Sub-resource levels should by <= 3
description: SHOULD limit number of sub-resource levels [147]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#147
severity: warn
given: $.paths.*~
then:
  function: pattern
  functionOptions:
    match: ^\/[^\/]*((\/{[^}]*})*\/[^\/]*(\/{[^}]*})*){0,3}\/?$
...message: Sub-resource levels should by <= 3
description: SHOULD limit number of sub-resource levels [147]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#147
severity: warn
given: $.paths.*~
then:
  function: pattern
  functionOptions:
    match: ^\/[^\/]*((\/{[^}]*})*\/[^\/]*(\/{[^}]*})*){0,3}\/?$