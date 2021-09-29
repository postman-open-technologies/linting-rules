---
severity: warn
message: 'Invalid property name: {{value}} (expected: lowercase with underscores)'
recommended: true
given: $.paths.*.*.parameters.*.name
then:
  function: pattern
  functionOptions:
    match: ^[a-z_]+$
...severity: warn
message: 'Invalid property name: {{value}} (expected: lowercase with underscores)'
recommended: true
given: $.paths.*.*.parameters.*.name
then:
  function: pattern
  functionOptions:
    match: ^[a-z_]+$