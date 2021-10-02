---
parameters-default-not-allowed:
  description: A required parameter should not specify a default value.
  severity: warn
  given:
  - $.paths[*].parameters.[?(@.required)]
  then:
    field: default
    function: falsy
...
parameters-default-not-allowed:
  description: A required parameter should not specify a default value.
  severity: warn
  given:
  - $.paths[*].parameters.[?(@.required)]
  then:
    field: default
    function: falsy