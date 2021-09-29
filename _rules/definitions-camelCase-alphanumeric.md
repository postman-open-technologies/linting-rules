---
description: All YAML/JSON definitions MUST follow fields-camelCase and be ASCII alphanumeric
  characters or `_` or `$`.
severity: error
recommended: true
message: '{{property}} MUST follow camelCase and be ASCII alphanumeric characters
  or `_` or `$`.'
given: $.definitions[*]~
then:
  function: pattern
  functionOptions:
    match: /^[a-z$_]{1}[A-Z09$_]*/
...description: All YAML/JSON definitions MUST follow fields-camelCase and be ASCII alphanumeric
  characters or `_` or `$`.
severity: error
recommended: true
message: '{{property}} MUST follow camelCase and be ASCII alphanumeric characters
  or `_` or `$`.'
given: $.definitions[*]~
then:
  function: pattern
  functionOptions:
    match: /^[a-z$_]{1}[A-Z09$_]*/