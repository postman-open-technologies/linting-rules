---
info-license-url:
  description: Should have a license url.
  given: $.info.license
  severity: error
  then:
    field: url
    function: truthy
  x-status: validated
  x-tags:
    - License
    - Legal     
...
info-license-url:
  description: Should have a license url.
  given: $.info.license
  severity: error
  then:
    field: url
    function: truthy
  x-status: validated
  x-tags:
    - License
    - Legal    