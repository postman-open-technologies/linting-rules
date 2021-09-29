---
description: Paths must be all lower-case (with exception for path variables), alphanumeric,
  with dashes and braces allowed
message: 'Paths must be all lower-case (with exception for path variables), alphanumeric,
  with dashes and braces allowed: {{property}}'
severity: error
given: $.paths
then:
  field: '@key'
  function: pattern
  functionOptions:
    match: ^(\/[a-z]+[0-9\-]*)+(\/[a-z0-9\-]+)*(\/{{1}(([a-z]+[0-9]*)([A-Z][a-z0-9]+)*)+}{1})*$
...description: Paths must be all lower-case (with exception for path variables), alphanumeric,
  with dashes and braces allowed
message: 'Paths must be all lower-case (with exception for path variables), alphanumeric,
  with dashes and braces allowed: {{property}}'
severity: error
given: $.paths
then:
  field: '@key'
  function: pattern
  functionOptions:
    match: ^(\/[a-z]+[0-9\-]*)+(\/[a-z0-9\-]+)*(\/{{1}(([a-z]+[0-9]*)([A-Z][a-z0-9]+)*)+}{1})*$