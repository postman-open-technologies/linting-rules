---
description: Absolutely must have the info information
given: $.info
message: Missing the {{property}}
severity: error
then:
- field: title
  function: truthy
- field: description
  function: truthy
- field: version
  function: truthy
...
given: $.info
message: Missing the {{property}}
severity: error
then:
- field: title
  function: truthy
- field: description
  function: truthy
- field: version
  function: truthy