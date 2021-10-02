---
operations-tags:
  severity: error
  message: Missing {{property}} at {{path}}.
  given: $.paths.*[get,post,patch,put,delete]
  then:
  - field: tags
    function: truthy
  x-status: validated
  x-tags:
    - Operations 
    - Tags   
...
operations-tags:
  severity: error
  message: Missing {{property}}at {{path}}
  given: $.paths.*[get,post,patch,put,delete]
  then:
  - field: tags
    function: truthy
  x-status: validated
  x-tags:
    - Operations  
    - Tags     