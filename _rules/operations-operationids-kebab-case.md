--- 
operations-operationids-kebab-case:
  description: "Operation IDs MUST be written in kebab-case."
  given: $.paths.*[get,post,patch,put,delete].operationId
  message: "{{property}} is not kebab-case {{error}}"
  recommended: true
  then:
      function: casing
      functionOptions:
          type: kebab
  type: style
  x-status: validated
  x-tags:
    - Operations
    - Casing  
...
operations-operationids-kebab-case:
  description: "Operation IDs MUST be written in kebab-case."
  given: $.paths.*[get,post,patch,put,delete]
  message: "{{property}} is not kebab-case {{error}}"
  recommended: true
    then:
        function: casing
        functionOptions:
            type: kebab
  type: style
  x-status: validated
  x-tags:
    - Operations
    - Casing  