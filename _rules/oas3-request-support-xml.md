---
description: Every request SHOULD support `application/xml` media type
formats:
- oas3
recommended: true
severity: warn
message: '{{description}}: {{error}}'
given: $.paths.[*].requestBody.content[?(@property.indexOf('xml') === -1)]^
then:
  function: falsy
...
description: Every request SHOULD support `application/xml` media type
formats:
- oas3
recommended: true
severity: warn
message: '{{description}}: {{error}}'
given: $.paths.[*].requestBody.content[?(@property.indexOf('xml') === -1)]^
then:
  function: falsy