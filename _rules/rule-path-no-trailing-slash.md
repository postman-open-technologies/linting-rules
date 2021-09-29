---
description: Paths should not end with `#/`.
given: $.paths[*]~
severity: error
then:
  function: pattern
  functionOptions:
    notMatch: .+\/$
type: style
...description: Paths should not end with `#/`.
given: $.paths[*]~
severity: error
then:
  function: pattern
  functionOptions:
    notMatch: .+\/$
type: style