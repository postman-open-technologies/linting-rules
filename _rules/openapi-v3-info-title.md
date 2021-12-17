---
description: Ensures that all OpenAPIs have a information object title.
message: The info object should have a title.
given: $.info
severity: error
recommended: true
type: style
formats:
  - oas3
then:
  field: title
  function: truthy
...
description: Ensures that all OpenAPIs have a information object title.
message: The info object should have a title.
given: $.info
severity: error
recommended: true
type: style
formats:
  - oas3
then:
  field: title
  function: truthy
