--- 
operation-summary-short: 
  description: "Operation summary should be short and sweet, no full stops, and less than 20 characters"
  given: "$.paths.*[?( @property === 'get' || @property === 'put' || @property === 'post' || @property === 'delete' || @property === 'options' || @property === 'head' || @property === 'patch' || @property === 'trace' )]"
  recommended: true
  then: 
    - 
      field: summary
      function: pattern
      functionOptions: 
        notMatch: \.
    - 
      field: summary
      function: length
      functionOptions: 
        max: 20
  type: style
...
operation-summary-short: 
  description: "Operation summary should be short and sweet, no full stops, and less than 20 characters"
  given: "$.paths.*[?( @property === 'get' || @property === 'put' || @property === 'post' || @property === 'delete' || @property === 'options' || @property === 'head' || @property === 'patch' || @property === 'trace' )]"
  recommended: true
  then: 
    - 
      field: summary
      function: pattern
      functionOptions: 
        notMatch: \.
    - 
      field: summary
      function: length
      functionOptions: 
        max: 20
  type: style