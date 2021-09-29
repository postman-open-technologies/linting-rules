---
description: All 'HTTP' headers SHOULD NOT include 'X-' headers (https://tools.ietf.org/html/rfc6648).
given: $..parameters[?(@.in == 'header')].name
message: HTTP headers SHOULD NOT include 'X-' prefix.
recommended: true
severity: warn
then:
  function: pattern
  functionOptions:
    notMatch: /^(x|X)-/
type: style
...description: All 'HTTP' headers SHOULD NOT include 'X-' headers (https://tools.ietf.org/html/rfc6648).
given: $..parameters[?(@.in == 'header')].name
message: HTTP headers SHOULD NOT include 'X-' prefix.
recommended: true
severity: warn
then:
  function: pattern
  functionOptions:
    notMatch: /^(x|X)-/
type: style