---
message: Header parameters should be Hyphenated-Pascal-Case
description: SHOULD prefer hyphenated-pascal-case for HTTP header fields [132]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#132
severity: warn
given: $.paths.*.*.parameters[?(@.in=='header')].name
then:
  function: pattern
  functionOptions:
    match: ^([A-Z][a-z]*)(-[A-Z0-9][a-z0-9]*)*$
...message: Header parameters should be Hyphenated-Pascal-Case
description: SHOULD prefer hyphenated-pascal-case for HTTP header fields [132]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#132
severity: warn
given: $.paths.*.*.parameters[?(@.in=='header')].name
then:
  function: pattern
  functionOptions:
    match: ^([A-Z][a-z]*)(-[A-Z0-9][a-z0-9]*)*$