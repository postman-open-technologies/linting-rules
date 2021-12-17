---
swagger-v2-operations-operation-ids-camel-case:
  description: Ensures that each of the operations IDs are camel case.
  message: Your operations IDs need to be camel case.
  given: $.paths.*[get,post,patch,put,delete].operationId
  recommended: true
  then:
    function: casing
    functionOptions:
      type: camel
  type: style
...
swagger-v2-operations-operation-ids-camel-case:
  description: Ensures that each of the operations IDs are camel case.
  message: Your operations IDs need to be camel case.
  given: $.paths.*[get,post,patch,put,delete].operationId
  recommended: true
  then:
    function: casing
    functionOptions:
      type: camel
  type: style
