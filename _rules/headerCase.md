---
description: Headers must start with X
message: '{{error}}'
recommended: true
type: style
given: $..parameters.[?(@.in === 'header')].name
severity: error
resolved: false
then:
  function: checkHyphenPascal
...description: Headers must start with X
message: '{{error}}'
recommended: true
type: style
given: $..parameters.[?(@.in === 'header')].name
severity: error
resolved: false
then:
  function: checkHyphenPascal