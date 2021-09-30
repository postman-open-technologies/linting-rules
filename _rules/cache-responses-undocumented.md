---
description: |-
  Cache usage SHOULD be extensively detailed in the `description` property
  to avoid data leaks or the usage of stale data.
message: Cache usage in responses SHOULD be documented in Cache-Control and/or Expires.
  {{error}}
formats:
- oas3
severity: info
recommended: true
given: $.[responses][?(@property[0] == "2" )][headers].[?(@property.match(/Cache-Control|Expires/i))]]
then:
- field: description
  function: truthy
- field: description
  function: pattern
  functionOptions:
    match: .*(max-age|private|no-store|no-cache).*
...
description: |-
  Cache usage SHOULD be extensively detailed in the `description` property
  to avoid data leaks or the usage of stale data.
message: Cache usage in responses SHOULD be documented in Cache-Control and/or Expires.
  {{error}}
formats:
- oas3
severity: info
recommended: true
given: $.[responses][?(@property[0] == "2" )][headers].[?(@property.match(/Cache-Control|Expires/i))]]
then:
- field: description
  function: truthy
- field: description
  function: pattern
  functionOptions:
    match: .*(max-age|private|no-store|no-cache).*