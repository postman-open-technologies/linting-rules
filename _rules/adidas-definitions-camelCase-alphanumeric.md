---
description: 'All YAML/JSON definitions MUST follow fields-camelCase and be ASCII alphanumeric
  characters.'
given: $.definitions[*]~
message: '{{property}} MUST follow camelCase and be ASCII alphanumeric characters.'
recommended: true
severity: error
then:
  function: pattern
  functionOptions:
    match: '/^[a-z$_]{1}[A-Z09$_]*/'
...
description: 'All YAML/JSON definitions MUST follow fields-camelCase and be ASCII alphanumeric
  characters.'
given: $.definitions[*]~
message: '{{property}} MUST follow camelCase and be ASCII alphanumeric characters.'
recommended: true
severity: error
then:
  function: pattern
  functionOptions:
    match: '/^[a-z$_]{1}[A-Z09$_]*/'