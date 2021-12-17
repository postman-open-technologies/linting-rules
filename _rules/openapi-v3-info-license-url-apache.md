---
openapi-v3-info-license-url-apache:
  description: Ensures that all OpenAPIs have a information object license url for Apache.
  message: The info object should have a license url for Apache.
  given: $.info.license.url
  severity: error
  then:
    function: pattern
    functionOptions:
      match: apache.org
...
openapi-v3-info-license-url-apache:
  description: Ensures that all OpenAPIs have a information object license url for Apache.
  message: The info object should have a license url for Apache.
  given: $.info.license.url
  severity: error
  then:
    function: pattern
    functionOptions:
      match: apache.org
