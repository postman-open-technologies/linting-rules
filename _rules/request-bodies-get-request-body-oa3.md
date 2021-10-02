--- 
request-bodies-get-request-body-oas3: 
  description: "GET methods must have a request body."
  given: $.paths.*.get
  message: "Method must not have a request body {{path}}"
  recommended: true
  severity: error
  then: 
    field: "requestBody"
    function: falsy
  x-status: validated
  x-tags:
    - Methods  
...
request-bodies-get-request-body-oas3: 
  description: "GET methods must have a request body."
  given: $.paths.*.get
  message: "Method must not have a request body {{path}}"
  recommended: true
  severity: error
  then: 
    field: "requestBody"
    function: falsy
  x-status: validated
  x-tags:
    - Methods 