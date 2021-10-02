--- 
request-bodies-patch-media-type: 
  description: "PATCH request bodies must have a application/json media type."
  given: $.paths.*.patch[requestBody].content
  message: "application/json is required for PATCH requests {{path}}"
  recommended: true
  severity: error
  then: 
    field: "application/json"
    function: truthy
  x-status: validated
  x-tags:
    - Methods  
...
request-bodies-post-media-type: 
  description: "POST request bodies must have a application/json media type."
  given: $.paths.*.post[requestBody].content
  message: "application/json is required for POST requests {{path}}"
  recommended: true
  severity: error
  then: 
    field: "application/json"
    function: truthy
  x-status: draft
  x-tags:
    - Tag 