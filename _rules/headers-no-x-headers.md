---
description: All 'HTTP' headers SHOULD NOT include 'X-' headers (https://tools.ietf.org/html/rfc6648).
severity: warn
given: $..parameters[?(@.in == 'header')].name
message: HTTP headers SHOULD NOT include 'X-' prefix.
recommended: true
type: style
then:
  function: pattern
  functionOptions:
    notMatch: /^(x|X)-/
...description: All 'HTTP' headers SHOULD NOT include 'X-' headers (https://tools.ietf.org/html/rfc6648).
severity: warn
given: $..parameters[?(@.in == 'header')].name
message: HTTP headers SHOULD NOT include 'X-' prefix.
recommended: true
type: style
then:
  function: pattern
  functionOptions:
    notMatch: /^(x|X)-/