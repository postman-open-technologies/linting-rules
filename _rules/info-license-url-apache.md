---
info-license-url-apache:
  description: Should have a license url.
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
...
info-license-url-apache:
  description: Should have a license url.
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