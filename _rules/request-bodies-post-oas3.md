--- 
request-bodies-post-oas3: 
  description: "POST methods must have a request body."
  given: $.paths.*.post
  message: "Method must have a request body {{path}}"
  recommended: true
  severity: error
  then: 
    field: "requestBody"
    function: truthy
  x-status: validated
  x-tags:
    - Methods  
...
request-bodies-post-oas3: 
  description: "POST methods must have a request body."
  given: $.paths.*.post
  message: "Method must have a request body {{path}}"
  recommended: true
  severity: error
  then: 
    field: "requestBody"
    function: truthy
  x-status: validated
  x-tags:
    - Methods 