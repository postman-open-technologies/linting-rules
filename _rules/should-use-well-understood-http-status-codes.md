---
message: '{{error}}'
description: MUST use standard HTTP status codes [150]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#150
severity: warn
given: $.paths.*
then:
  function: assert-http-codes-for-operation
  functionOptions:
    wellUnderstood:
      200:
      - ALL
      201:
      - POST
      - PUT
      202:
      - POST
      - PUT
      - DELETE
      - PATCH
      204:
      - PUT
      - DELETE
      - PATCH
      207:
      - POST
      301:
      - ALL
      303:
      - PATCH
      - POST
      - PUT
      - DELETE
      304:
      - GET
      - HEAD
      400:
      - ALL
      401:
      - ALL
      403:
      - ALL
      404:
      - ALL
      405:
      - ALL
      406:
      - ALL
      408:
      - ALL
      409:
      - POST
      - PUT
      - DELETE
      - PATCH
      410:
      - ALL
      412:
      - PUT
      - DELETE
      - PATCH
      415:
      - POST
      - PUT
      - DELETE
      - PATCH
      423:
      - PUT
      - DELETE
      - PATCH
      428:
      - ALL
      429:
      - ALL
      500:
      - ALL
      501:
      - ALL
      503:
      - ALL
      default:
      - ALL
...message: '{{error}}'
description: MUST use standard HTTP status codes [150]
documentationUrl: https://opensource.zalando.com/restful-api-guidelines/#150
severity: warn
given: $.paths.*
then:
  function: assert-http-codes-for-operation
  functionOptions:
    wellUnderstood:
      200:
      - ALL
      201:
      - POST
      - PUT
      202:
      - POST
      - PUT
      - DELETE
      - PATCH
      204:
      - PUT
      - DELETE
      - PATCH
      207:
      - POST
      301:
      - ALL
      303:
      - PATCH
      - POST
      - PUT
      - DELETE
      304:
      - GET
      - HEAD
      400:
      - ALL
      401:
      - ALL
      403:
      - ALL
      404:
      - ALL
      405:
      - ALL
      406:
      - ALL
      408:
      - ALL
      409:
      - POST
      - PUT
      - DELETE
      - PATCH
      410:
      - ALL
      412:
      - PUT
      - DELETE
      - PATCH
      415:
      - POST
      - PUT
      - DELETE
      - PATCH
      423:
      - PUT
      - DELETE
      - PATCH
      428:
      - ALL
      429:
      - ALL
      500:
      - ALL
      501:
      - ALL
      503:
      - ALL
      default:
      - ALL