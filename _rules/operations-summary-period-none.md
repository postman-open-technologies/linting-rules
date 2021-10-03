---
operations-summary-period-none:
  severity: error
  description: 'Summary should not have a trailing period'
  message: Missing {{property}} at {{path}}.
  given: $.paths[*][*].summary
  then:
    function: pattern
    functionOptions:
      notMatch: "\\.$"  
  x-status: validated
  x-tags:
    - Operations    
...
operations-summary-period-none:
  severity: error
  description: 'Summary should not have a trailing period'
  message: Missing {{property}} at {{path}}.
  given: $.paths[*][*].summary
  then:
    function: pattern
    functionOptions:
      notMatch: "\\.$"  
  x-status: validated
  x-tags:
    - Operations      