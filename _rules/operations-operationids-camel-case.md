--- 
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