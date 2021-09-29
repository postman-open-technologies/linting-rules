---
description: ALL requests MUST go through `https` protocol only
formats:
- oas3
severity: error
message: Servers MUST be https and no other protocol is allowed.
given: $.servers..url
then:
  function: pattern
  functionOptions:
    match: /^https:/
...description: ALL requests MUST go through `https` protocol only
formats:
- oas3
severity: error
message: Servers MUST be https and no other protocol is allowed.
given: $.servers..url
then:
  function: pattern
  functionOptions:
    match: /^https:/