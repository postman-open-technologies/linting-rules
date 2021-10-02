--- 
operation-description-length: 
  description: "Operation description should be short and sweet, no full stops, and less than 20 characters"
  given: $.paths.*[get,post,patch,put,delete]
  recommended: true
  then: 
    - field: description
      function: length
      functionOptions: 
        max: 20
  type: style
  x-status: validated
  x-tags:
    - Operations
    - Length  
...
operation-description-length: 
  description: "Operation description should be short and sweet, no full stops, and less than 20 characters"
  given: $.paths.*[get,post,patch,put,delete]
  recommended: true
  then: 
    - field: description
      function: length
      functionOptions: 
        max: 20
  type: style
  x-status: validated
  x-tags:
    - Operations
    - Length  