---
openapi-v3-response-rate-limit-headers:
  description: Ensures that all OpenAPIs have rate limiting headers applied.
  message: You need to be using rate limiting headers.
  formats:
    - oas3
  severity: warn
  recommended: true
  given: $.[responses][?(@property[0] == "2" )][headers]
  then:
    - functionOptions:
        properties:
          - X-RateLimit-Limit
          - RateLimit-Limit
      function: xor
    - functionOptions:
        properties:
          - X-RateLimit-Remaining
          - RateLimit-Remaining
      function: xor
    - functionOptions:
        properties:
          - X-RateLimit-Reset
          - RateLimit-Reset
      function: xor
...
openapi-v3-response-rate-limit-headers:
  description: Ensures that all OpenAPIs have rate limiting headers applied.
  message: You need to be using rate limiting headers.
  formats:
    - oas3
  severity: warn
  recommended: true
  given: $.[responses][?(@property[0] == "2" )][headers]
  then:
    - functionOptions:
        properties:
          - X-RateLimit-Limit
          - RateLimit-Limit
      function: xor
    - functionOptions:
        properties:
          - X-RateLimit-Remaining
          - RateLimit-Remaining
      function: xor
    - functionOptions:
        properties:
          - X-RateLimit-Reset
          - RateLimit-Reset
      function: xor
