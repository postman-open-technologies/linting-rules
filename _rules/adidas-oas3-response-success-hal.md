---
description: 'All success responses MUST be of media type `application/hal+json` '
formats:
- oas3
given: $.paths..responses[?( @property >= 201 && @property < 300 && @property != 204)].content[*]~
message: 'Response documents MUST be of application/hal+json media types: {{error}}'
recommended: true
severity: error
then:
  function: enumeration
  functionOptions:
    values:
    - application/hal+json
...description: 'All success responses MUST be of media type `application/hal+json` '
formats:
- oas3
given: $.paths..responses[?( @property >= 201 && @property < 300 && @property != 204)].content[*]~
message: 'Response documents MUST be of application/hal+json media types: {{error}}'
recommended: true
severity: error
then:
  function: enumeration
  functionOptions:
    values:
    - application/hal+json