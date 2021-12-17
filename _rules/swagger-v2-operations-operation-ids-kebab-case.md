---
swagger-v2-operations-operation-ids-kebab-case:
  description: Ensures that each of the operations IDs are kebab case.
  message: Your operations IDs need to be kebab case.
  given: $.paths.*[get,post,patch,put,delete].operationId
  recommended: true
  then:
    function: casing
    functionOptions:
      type: kebab
  type: style
...
swagger-v2-operations-operation-ids-kebab-case:
  description: Ensures that each of the operations IDs are kebab case.
  message: Your operations IDs need to be kebab case.
  given: $.paths.*[get,post,patch,put,delete].operationId
  recommended: true
  then:
    function: casing
    functionOptions:
      type: kebab
  type: style
