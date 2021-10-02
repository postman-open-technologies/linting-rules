---
operations-summary:
  severity: error
  message: Missing {{property}} at {{path}}.
  given: $.paths.*[get,post,patch,put,delete]
  then:
  - field: summary
    function: truthy
...
operations-summary:
  severity: error
  message: Missing {{property}}at {{path}}
  given: $.paths.*[get,post,patch,put,delete]
  then:
  - field: summary
    function: truthy