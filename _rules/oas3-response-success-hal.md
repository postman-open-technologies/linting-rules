---
description: All success responses MUST be of media type `application/hal+json`
severity: error
given: $.paths..responses[?( @property >= 200 && @property < 300 && @property != 204)].content[*]~
recommended: true
formats:
- oas3
message: 'Response documents MUST be of application/json media type: {{error}}'
then:
  function: enumeration
  functionOptions:
    values:
    - application/json
...
description: All success responses MUST be of media type `application/hal+json`
severity: error
given: $.paths..responses[?( @property >= 200 && @property < 300 && @property != 204)].content[*]~
recommended: true
formats:
- oas3
message: 'Response documents MUST be of application/json media type: {{error}}'
then:
  function: enumeration
  functionOptions:
    values:
    - application/json