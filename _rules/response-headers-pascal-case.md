---
x-tags:
- it
description: |
  Headers should be pascal-case.
message: 'Header {{error}}: {{path}}'
severity: hint
recommended: true
given:
- $.[responses][*].headers.*~
then:
  function: casing
  functionOptions:
    type: pascal
    separator:
      char: '-'
...
x-tags:
- it
description: |
  Headers should be pascal-case.
message: 'Header {{error}}: {{path}}'
severity: hint
recommended: true
given:
- $.[responses][*].headers.*~
then:
  function: casing
  functionOptions:
    type: pascal
    separator:
      char: '-'