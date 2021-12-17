---
swagger-v2-no-empty-paths:
  description: Ensures that there are no empty paths.
  message: There should be no empty paths.
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#136
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: //
...
swagger-v2-no-empty-paths:
  description: Ensures that there are no empty paths.
  message: There should be no empty paths.
  documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#136
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: //
