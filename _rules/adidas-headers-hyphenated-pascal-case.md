---
description: All `HTTP` headers MUST use `Hyphenated-Pascal-Case` notation
given: $..parameters[?(@.in == 'header')].name
message: '''HTTP'' headers MUST follow ''Hyphenated-Pascal-Case'' notation'
recommended: true
severity: error
then:
  function: pattern
  functionOptions:
    match: /^([A-Z][a-z0-9]-)*([A-Z][a-z0-9])+/
type: style
...description: All `HTTP` headers MUST use `Hyphenated-Pascal-Case` notation
given: $..parameters[?(@.in == 'header')].name
message: '''HTTP'' headers MUST follow ''Hyphenated-Pascal-Case'' notation'
recommended: true
severity: error
then:
  function: pattern
  functionOptions:
    match: /^([A-Z][a-z0-9]-)*([A-Z][a-z0-9])+/
type: style