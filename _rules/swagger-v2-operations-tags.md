---
swagger-v2-operations-tags:
  description: Ensures that each of the operations have a tags property.
  message: All of your operations need to have tags.
  severity: error
  given: $.paths.*[get,post,patch,put,delete]
  then:
    - field: tags
      function: truthy
...
swagger-v2-operations-tags:
  description: Ensures that each of the operations have a tags property.
  message: All of your operations need to have tags.
  severity: error
  given: $.paths.*[get,post,patch,put,delete]
  then:
    - field: tags
      function: truthy
