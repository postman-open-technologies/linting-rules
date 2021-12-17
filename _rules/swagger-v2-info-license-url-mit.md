---
swagger-v2-info-license-url-mit:
  description: Ensures that all Swaggers have a information object license url for MIT.
  message: The info object should have a license url for MIT.
  given: $.info.license.url
  severity: error
  then:
    function: pattern
    functionOptions:
      match: mit.edu
...
swagger-v2-info-license-url-mit:
  description: Ensures that all Swaggers have a information object license url for MIT.
  message: The info object should have a license url for MIT.
  given: $.info.license.url
  severity: error
  then:
    function: pattern
    functionOptions:
      match: mit.edu
