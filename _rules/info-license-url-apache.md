---
info-license-url-apache:
  description: API must have an Apache license applied.
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
  description: API must have an Apache license applied.
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