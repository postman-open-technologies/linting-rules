---
no-x-headers-response:
  x-tags:
    - standards
  description: "'HTTP' headers SHOULD NOT start with 'X-' RFC6648."
  severity: warn
  given:
    - $.[responses][*].headers.*~
  message: HTTP response header SHOULD NOT start with 'X-' in {{path}}
  recommended: true
  type: style
  then:
    function: pattern
    functionOptions:
      match: /^([^x]|.[^-])|RateLimit-/i    
  x-status: draft
  x-tags:
      - Tag          
...
no-x-headers-response:
  x-tags:
    - standards
  description: "'HTTP' headers SHOULD NOT start with 'X-' RFC6648."
  severity: warn
  given:
    - $.[responses][*].headers.*~
  message: HTTP response header SHOULD NOT start with 'X-' in {{path}}
  recommended: true
  type: style
  then:
    function: pattern
    functionOptions:
      match: /^([^x]|.[^-])|RateLimit-/i  
  x-status: draft
  x-tags:
      - Tag         
