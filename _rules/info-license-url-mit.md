---
info-license-url:
  description: Should have an MIT license.
  given: $.info.license.url
  severity: error
  then:
    function: pattern
    functionOptions:
      match: apache.org
  x-status: validated
  x-tags:
    - License
    - Legal  
    - MIT   
...
info-license-url:
  description: Should have an MIT license.
  given: $.info.license.url
  severity: error
  then:
    function: pattern
    functionOptions:
      match: apache.org
  x-status: validated
  x-tags:
    - License
    - Legal  
    - MIT     