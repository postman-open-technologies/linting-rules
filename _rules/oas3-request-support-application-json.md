---
description: Every request MUST support `application/json` media type
formats:
- oas3
recommended: true
severity: error
message: '{{description}}: {{error}}'
given: $.paths.[*].requestBody.content[?(@property.indexOf('json') === -1)]^
then:
  function: falsy
...description: Every request MUST support `application/json` media type
formats:
- oas3
recommended: true
severity: error
message: '{{description}}: {{error}}'
given: $.paths.[*].requestBody.content[?(@property.indexOf('json') === -1)]^
then:
  function: falsy