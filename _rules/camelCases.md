---
description: Must be camel case
message: Property names must be camel case, please find new value for {{path}}.
recommended: true
type: style
given: $.paths.*.*~
severity: error
resolved: false
then:
  function: casing
  functionOptions:
    type: camel
...
message: Property names must be camel case, please find new value for {{path}}.
recommended: true
type: style
given: $.paths.*.*~
severity: error
resolved: false
then:
  function: casing
  functionOptions:
    type: camel