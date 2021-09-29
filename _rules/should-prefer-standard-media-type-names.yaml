---
message: Custom media types should only be used for versioning
description: SHOULD prefer standard media type name application/json [172]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#172
severity: warn
given: $.paths.*.*.responses.*.content.*~
then:
  function: pattern
  functionOptions:
    match: ^application\/(problem\+)?json$|^[a-zA-Z0-9_]+\/[-+.a-zA-Z0-9_]+;(v|version)=[0-9]+$
...message: Custom media types should only be used for versioning
description: SHOULD prefer standard media type name application/json [172]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#172
severity: warn
given: $.paths.*.*.responses.*.content.*~
then:
  function: pattern
  functionOptions:
    match: ^application\/(problem\+)?json$|^[a-zA-Z0-9_]+\/[-+.a-zA-Z0-9_]+;(v|version)=[0-9]+$