---
description: Each operation must have a description which cannot be empty.
given: $.paths.[*][get,post,put,delete,options]
severity: error
then:
  field: description
  function: truthy
...description: Each operation must have a description which cannot be empty.
given: $.paths.[*][get,post,put,delete,options]
severity: error
then:
  field: description
  function: truthy