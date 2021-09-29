---
description: Every request MUST support `application/json` media type
formats:
- oas3
given: $.paths.[*].requestBody.content[?(@property.indexOf('json') === -1)]^
message: '{{description}}: {{error}}'
recommended: true
severity: error
then:
  function: falsy
...description: Every request MUST support `application/json` media type
formats:
- oas3
given: $.paths.[*].requestBody.content[?(@property.indexOf('json') === -1)]^
message: '{{description}}: {{error}}'
recommended: true
severity: error
then:
  function: falsy