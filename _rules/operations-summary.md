---
operations-summary:
  severity: error
  message: Missing {{property}} at {{path}}.
  given: $.paths.*[get,post,patch,put,delete]
  then:
  - field: summary
    function: truthy
  x-status: validated
  x-tags:
    - Operations    
...
operations-summary:
  severity: error
  message: Missing {{property}}at {{path}}
  given: $.paths.*[get,post,patch,put,delete]
  then:
  - field: summary
    function: truthy
  x-status: validated
  x-tags:
    - Operations       