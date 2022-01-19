--- 
openapi-v3-version-semantic: 
  description: "Ensuring that semantic versioning is being used."
  given: $.info.version
  message: "You need to provide a semantic version."
  recommended: true
  severity: error
  then: 
    function: pattern
    functionOptions: 
      match: "^[0-9]+.[0-9]+.[0-9]+(-[a-z0-9+.-]+)?"
...
openapi-v3-version-semantic: 
  description: "Ensuring that semantic versioning is being used."
  given: $.info.version
  message: "You need to provide a semantic version."
  recommended: true
  severity: error
  then: 
    function: pattern
    functionOptions: 
      match: "^[0-9]+.[0-9]+.[0-9]+(-[a-z0-9+.-]+)?"

