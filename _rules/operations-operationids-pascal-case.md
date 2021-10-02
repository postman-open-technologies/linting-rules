--- 
operations-operationids-pascal-case:
  description: "Operation IDs MUST be written in PascalCase."
  given: $.paths.*[get,post,patch,put,delete].operationId
  message: "{{property}} is not PascalCase {{error}}"
  recommended: true
  then:
      function: casing
      functionOptions:
          type: pascal
  type: style
  x-status: validated
  x-tags:
    - Operations
    - Casing 
...
operations-operationids-pascal-case:
  description: "Operation IDs MUST be written in PascalCase."
  given: $.paths.*[get,post,patch,put,delete]
  message: "{{property}} is not PascalCase {{error}}"
  recommended: true
    then:
        function: casing
        functionOptions:
            type: pascal
  type: style
  x-status: validated
  x-tags:
    - Operations
    - Casing   