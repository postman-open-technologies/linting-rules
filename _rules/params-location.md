---
severity: error
description: Required parameters must be in the URL path or header
given: $..parameters[?(@.in != 'path' && @.in != 'header')]
then:
  field: required
  function: falsy
...
description: Required parameters must be in the URL path or header
given: $..parameters[?(@.in != 'path' && @.in != 'header')]
then:
  field: required
  function: falsy