---
description: OperationId should conform to Azure API Guidelines
message: '{{error}}'
severity: warn
given:
- $.paths.*[get,put,post,patch,delete,options,head]
then:
  function: operation-id
...description: OperationId should conform to Azure API Guidelines
message: '{{error}}'
severity: warn
given:
- $.paths.*[get,put,post,patch,delete,options,head]
then:
  function: operation-id