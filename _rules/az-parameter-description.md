---
description: All parameters should have a description.
message: Parameter should have a description.
severity: warn
given:
- $.paths[*].parameters.*
- $.paths.*[get,put,post,patch,delete,options,head].parameters.*
then:
  field: description
  function: truthy
...
message: Parameter should have a description.
severity: warn
given:
- $.paths[*].parameters.*
- $.paths.*[get,put,post,patch,delete,options,head].parameters.*
then:
  field: description
  function: truthy