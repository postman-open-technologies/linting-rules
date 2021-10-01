--- 
api-home-get: 
  description: "APIs root path MUST have a GET defined,."
  formats: 
    - oas2
    - oas3
  given: "$.paths[/]"
  severity: warn
  then: 
    field: get
    function: truthy  
  x-status: draft
  x-tags:
    - Tag       
...
api-home-get: 
  description: "APIs root path MUST have a GET defined,."
  formats: 
    - oas2
    - oas3
  given: "$.paths[/]"
  severity: warn
  then: 
    field: get
    function: truthy
  x-status: draft
  x-tags:
    - Tag    