---
description: Cache usage SHOULD be extensively detailed in the `description` property
  to avoid data leaks or the usage of stale data.
message: Cache usage SHOULD be documented when used.
formats:
- oas3
severity: warn
recommended: true
given: $..[parameters][?(@.in == "header" && @.name.match(/Cache-Control/i))]
then:
- field: description
  function: truthy
- field: description
  function: pattern
  functionOptions:
    match: .*(max-age|private|no-store|no-cache).*
...
description: Cache usage SHOULD be extensively detailed in the `description` property
  to avoid data leaks or the usage of stale data.
message: Cache usage SHOULD be documented when used.
formats:
- oas3
severity: warn
recommended: true
given: $..[parameters][?(@.in == "header" && @.name.match(/Cache-Control/i))]
then:
- field: description
  function: truthy
- field: description
  function: pattern
  functionOptions:
    match: .*(max-age|private|no-store|no-cache).*