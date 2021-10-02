--- 
operations-operationids-camel-case:
  description: "Operation IDs MUST be written in camelCase."
  given: $.paths.*[get,post,patch,put,delete].operationId
  message: "{{property}} is not camelCase {{error}}"
  recommended: true
  then:
      function: casing
      functionOptions:
          type: camel
  type: style
  x-status: validated
  x-tags:
    - Operations
    - Casing
...
operations-operationids-camel-case:
  description: "Operation IDs MUST be written in camelCase."
  given: $.paths.*[get,post,patch,put,delete]
  message: "{{property}} is not camelCase {{error}}"
  recommended: true
    then:
        function: casing
        functionOptions:
            type: camel
  type: style
  x-status: validated
  x-tags:
    - Operations
    - Casing  