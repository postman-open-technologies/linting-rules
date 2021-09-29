---
description: All success responses except 202 & 204 should define a response body.
severity: warn
formats:
- oas2
given: $.paths[*][*].responses[?(@property >= 200 && @property < 300 && @property
  != '202' && @property != '204')]
then:
  field: schema
  function: truthy
...
severity: warn
formats:
- oas2
given: $.paths[*][*].responses[?(@property >= 200 && @property < 300 && @property
  != '202' && @property != '204')]
then:
  field: schema
  function: truthy