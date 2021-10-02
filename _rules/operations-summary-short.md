--- 
operation-summary-short: 
  description: "Operation summary should be short and sweet, no full stops, and less than 20 characters"
  given: $.paths.*[get,post,patch,put,delete]
  recommended: true
  then: 
    - field: summary
      function: length
      functionOptions: 
        max: 20
  type: style
  x-status: validated
  x-tags:
    - Operations
    - Length  
...
operation-summary-short: 
  description: "Operation summary should be short and sweet, no full stops, and less than 20 characters"
  given: $.paths.*[get,post,patch,put,delete]
  recommended: true
  then: 
    - field: summary
      function: length
      functionOptions: 
        max: 20
  type: style
  x-status: validated
  x-tags:
    - Operations
    - Length  