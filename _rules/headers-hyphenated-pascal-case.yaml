---
severity: error
given: $..parameters[?(@.in == 'header')].name
description: '''HTTP'' headers MUST follow ''Hyphenated-Pascal-Case'' notation'
then:
  function: pattern
  functionOptions:
    match: /^([A-Z][a-z0-9]-)*([A-Z][a-z0-9])+/
...severity: error
given: $..parameters[?(@.in == 'header')].name
description: '''HTTP'' headers MUST follow ''Hyphenated-Pascal-Case'' notation'
then:
  function: pattern
  functionOptions:
    match: /^([A-Z][a-z0-9]-)*([A-Z][a-z0-9])+/