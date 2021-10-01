--- 
response-body-standard-oas2: 
  description: "Ensure the get, put, and patch response body schemas are consistent."
  formats: 
    - oas2
  given: $.paths.*
  message: "{{error}}"
  severity: warn
  then: 
    function: consistent-response-body
  x-tags: 
    - Responses  
  x-status: draft
  x-tags:
    - Tag     
...
response-body-standard-oas2: 
  description: "Ensure the get, put, and patch response body schemas are consistent."
  formats: 
    - oas2
  given: $.paths.*
  message: "{{error}}"
  severity: warn
  then: 
    function: consistent-response-body
  x-tags: 
    - Responses  
  x-status: draft
  x-tags:
    - Tag    