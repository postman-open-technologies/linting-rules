---
description: Response must include ratelimit-x headers
message: '{{description}}; missing {{property}}'
severity: error
given: $..responses.*
then:
- field: headers.ratelimit-limit
  function: truthy
- field: headers.ratelimit-remaining
  function: truthy
- field: headers.ratelimit-reset
  function: truthy
...description: Response must include ratelimit-x headers
message: '{{description}}; missing {{property}}'
severity: error
given: $..responses.*
then:
- field: headers.ratelimit-limit
  function: truthy
- field: headers.ratelimit-remaining
  function: truthy
- field: headers.ratelimit-reset
  function: truthy