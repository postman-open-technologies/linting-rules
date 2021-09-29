---
description: All YAML/JSON paths MUST follow camelCase
severity: warn
recommended: true
message: '{{property}} is not camelCase: {{error}}'
given: $.paths[*]~
then:
  function: pattern
  functionOptions:
    match: ^/([a-z][a-zA-Z0-9]+)?(/[a-z][a-zA-Z0-9]+|/{[a-z][a-zA-Z0-9]+})*$
...description: All YAML/JSON paths MUST follow camelCase
severity: warn
recommended: true
message: '{{property}} is not camelCase: {{error}}'
given: $.paths[*]~
then:
  function: pattern
  functionOptions:
    match: ^/([a-z][a-zA-Z0-9]+)?(/[a-z][a-zA-Z0-9]+|/{[a-z][a-zA-Z0-9]+})*$