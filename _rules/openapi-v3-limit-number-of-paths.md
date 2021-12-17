---
openapi-v3-limit-number-of-paths:
  description: Ensures that there are not too many paths.
  message: There should be no more than 10 paths.
  severity: warn
  given: $.paths
  then:
    function: count-resource-types
    functionOptions:
      max: 10
...
openapi-v3-limit-number-of-paths:
  description: Ensures that there are not too many paths.
  message: There should be no more than 10 paths.
  severity: warn
  given: $.paths
  then:
    function: count-resource-types
    functionOptions:
      max: 10
