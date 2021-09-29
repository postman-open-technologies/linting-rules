---
description: A 'GET' request MUST NOT accept a 'body` parameter
severity: error
given: $.paths..get.parameters..in
then:
  function: pattern
  functionOptions:
    notMatch: /^body$/
...description: A 'GET' request MUST NOT accept a 'body` parameter
severity: error
given: $.paths..get.parameters..in
then:
  function: pattern
  functionOptions:
    notMatch: /^body$/