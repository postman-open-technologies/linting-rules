---
description: A get or delete operation must not accept a body parameter.
severity: error
formats:
- oas2
given:
- $.paths[*].[get,delete].parameters[*]
then:
  field: in
  function: pattern
  functionOptions:
    notMatch: /^body$/
...description: A get or delete operation must not accept a body parameter.
severity: error
formats:
- oas2
given:
- $.paths[*].[get,delete].parameters[*]
then:
  field: in
  function: pattern
  functionOptions:
    notMatch: /^body$/