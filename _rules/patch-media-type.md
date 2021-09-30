---
x-tags:
- standards
description: |-
  The PATCH specification explicits that the request body contains
  a "patch document" describing the changes to be applied
  to the target resource.
message: application/json is not an appropriate media-type for PATCH. {{path}}
formats:
- oas3
severity: error
recommended: true
given: $.[patch][requestBody][content]
then:
  field: application/json
  function: falsy
...
x-tags:
- standards
description: |-
  The PATCH specification explicits that the request body contains
  a "patch document" describing the changes to be applied
  to the target resource.
  ```
message: application/json is not an appropriate media-type for PATCH. {{path}}
formats:
- oas3
severity: error
recommended: true
given: $.[patch][requestBody][content]
then:
  field: application/json
  function: falsy