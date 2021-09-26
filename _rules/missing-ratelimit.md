---
missing-ratelimit:
  x-tags:
    - it
  description: >-
    Ratelimiting API preserves a service and limits attack scenario [see API4:2019 Lack of Resources & Rate Limiting](https://owasp.org/www-project-api-security). APIs should use the following headers at least on successful responses:

    - `X-RateLimit-Limit`: number of total requests in a give time window
    - `X-RateLimit-Remaining`: remaining requests in the current window
    - `X-RateLimit-Reset`: number of seconds before the window resets

    An example set of headers is the following

    ```

    X-Ratelimit-Limit: 100

    X-Ratelimit-Remaining: 40

    X-Ratelimit-Reset: 12

    ```
    A standardization proposal for ratelimit headers is ongoning inside the IETF HTTPAPI Workgroup. See [the draft](https://datatracker.ietf.org/doc/draft-ietf-httpapi-ratelimit-headers/)
  message: Missing ratelimit headers. {{property}} {{error}} {{path}}
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
missing-ratelimit:
  x-tags:
    - it
  description: >-
    Ratelimiting API preserves a service and limits attack scenario [see API4:2019 Lack of Resources & Rate Limiting](https://owasp.org/www-project-api-security). APIs should use the following headers at least on successful responses:

    - `X-RateLimit-Limit`: number of total requests in a give time window
    - `X-RateLimit-Remaining`: remaining requests in the current window
    - `X-RateLimit-Reset`: number of seconds before the window resets

    An example set of headers is the following

    ```

    X-Ratelimit-Limit: 100

    X-Ratelimit-Remaining: 40

    X-Ratelimit-Reset: 12

    ```
    A standardization proposal for ratelimit headers is ongoning inside the IETF HTTPAPI Workgroup. See [the draft](https://datatracker.ietf.org/doc/draft-ietf-httpapi-ratelimit-headers/)
  message: Missing ratelimit headers. {{property}} {{error}} {{path}}
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