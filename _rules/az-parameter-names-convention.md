---
description: Parameter names should conform to Azure naming conventions.
message: '{{error}}'
severity: warn
given:
- $.paths[*].parameters.*
- $.paths.*[get,put,post,patch,delete,options,head].parameters.*
then:
  function: param-names
...
message: '{{error}}'
severity: warn
given:
- $.paths[*].parameters.*
- $.paths.*[get,put,post,patch,delete,options,head].parameters.*
then:
  function: param-names