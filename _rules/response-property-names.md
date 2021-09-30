---
severity: warn
message: 'Invalid response property name: {{property}} (expected: lowercase with underscores)'
recommended: true
given: $..components.schemas.*.properties[*]~
then:
  function: pattern
  functionOptions:
    match: ^[a-z_]+$
...
severity: warn
message: 'Invalid response property name: {{property}} (expected: lowercase with underscores)'
recommended: true
given: $..components.schemas.*.properties[*]~
then:
  function: pattern
  functionOptions:
    match: ^[a-z_]+$