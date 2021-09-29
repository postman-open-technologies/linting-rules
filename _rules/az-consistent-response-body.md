---
description: Ensure the get, put, and patch response body schemas are consistent.
message: '{{error}}'
severity: warn
formats:
- oas2
given: $.paths.*
then:
  function: consistent-response-body
...description: Ensure the get, put, and patch response body schemas are consistent.
message: '{{error}}'
severity: warn
formats:
- oas2
given: $.paths.*
then:
  function: consistent-response-body