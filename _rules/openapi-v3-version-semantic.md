---
openapi-v3-version-semantic:
  description: Ensuring that semantic versioning is being used.
  message: You need to provide a semantic version.
  severity: error
  recommended: true
  given: $.info.version
  then:
    function: pattern
    functionOptions: null
    match: ^[0-9]+.[0-9]+.[0-9]+(-[a-z0-9+.-]+)?
...
openapi-v3-version-semantic:
  description: Ensuring that semantic versioning is being used.
  message: You need to provide a semantic version.
  severity: error
  recommended: true
  given: $.info.version
  then:
    function: pattern
    functionOptions:
         match: ^[0-9]+.[0-9]+.[0-9]+(-[a-z0-9+.-]+)?
