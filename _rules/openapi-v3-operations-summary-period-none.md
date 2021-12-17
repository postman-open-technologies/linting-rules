---
openapi-v3-operations-summary-period-none:
  severity: error
  description: Ensures that each of the operations summaries do not have an ending period.
  message: Your operations summaries should not end with a period.
  given: $.paths[*][*].summary
  then:
    function: pattern
    functionOptions:
      notMatch: \.$
...
openapi-v3-operations-summary-period-none:
  severity: error
  description: Ensures that each of the operations summaries do not have an ending period.
  message: Your operations summaries should not end with a period.
  given: $.paths[*][*].summary
  then:
    function: pattern
    functionOptions:
      notMatch: \.$
