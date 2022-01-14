---
openapi-v3-operations-operation-ids-pascal-case:
  description: Ensures that each of the operations IDs are pascal case.
  message: Your operations IDs need to be pascal case.
  given: $.paths.*[get,post,patch,put,delete].operationId
  recommended: true
  then:
    function: casing
    functionOptions:
      type: pascal
  type: style
...
openapi-v3-operations-operation-ids-pascal-case:
  description: Ensures that each of the operations IDs are pascal case.
  message: Your operations IDs need to be pascal case.
  given: $.paths.*[get,post,patch,put,delete].operationId
  recommended: true
  then:
    function: casing
    functionOptions:
      type: pascal
  type: style
