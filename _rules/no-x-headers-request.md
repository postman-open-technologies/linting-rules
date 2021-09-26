---
no-x-headers-request:
  x-tags:
    - standards
  description: "'HTTP' headers SHOULD NOT start with 'X-' RFC6648."
  severity: warn
  given:
    - $..parameters[?(@.in == 'header')].name
  message: HTTP header '{{value}}' SHOULD NOT start with 'X-' in {{path}}
  recommended: true
  type: style
  then:
    function: pattern
    functionOptions:
      match: /^([^x]|.[^-])|RateLimit-/i    
...
no-x-headers-request:
  x-tags:
    - standards
  description: "'HTTP' headers SHOULD NOT start with 'X-' RFC6648."
  severity: warn
  given:
    - $..parameters[?(@.in == 'header')].name
  message: HTTP header '{{value}}' SHOULD NOT start with 'X-' in {{path}}
  recommended: true
  type: style
  then:
    function: pattern
    functionOptions:
      match: /^([^x]|.[^-])|RateLimit-/i    
