---
info-license-name:
  description: API must have a license name applied.
  given: $.info.license
  severity: error
  then:
    field: name
    function: truthy
  x-status: validated
  x-tags:
    - License
    - Legal    
...
info-license-name:
  description: API must have a license name applied.
  given: $.info.license
  severity: error
  then:
    field: name
    function: truthy
  x-status: validated
  x-tags:
    - License
    - Legal   