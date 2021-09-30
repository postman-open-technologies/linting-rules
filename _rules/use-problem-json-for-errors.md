---
use-problem-json-for-errors:
  description: |-
    
    Error management is a key enabler of a resilient API ecosystem.
    Enforcing a consistent schema for errors between different APIs,
    enables client to properly implement an error management strategy,
    with positive impacts for users.

    Error responses should return one of the media-type
    defined in RFC7807:
    - `application/problem+json`
    - `application/problem+xml`

    An example of a valid response:

    ```
    responses:
      "503":
        content:
          application/problem+json:
            schema:
              ...
    ```
  message: Error responses should support RFC7807 in {{path}}.
  formats:
    - oas3
  severity: error
  given: $.paths.[*].responses[?(@property.match(/^(4|5|default)/))].content.*~
  then:
    function: enumeration
    functionOptions:
      values:
        - application/problem+xml
        - application/problem+json   
...
use-problem-json-for-errors:
  description: |-
    
    Error management is a key enabler of a resilient API ecosystem.
    Enforcing a consistent schema for errors between different APIs,
    enables client to properly implement an error management strategy,
    with positive impacts for users.

    Error responses should return one of the media-type
    defined in RFC7807:
    - `application/problem+json`
    - `application/problem+xml`

    An example of a valid response:

    ```
    responses:
      "503":
        content:
          application/problem+json:
            schema:
              ...
    ```
  message: Error responses should support RFC7807 in {{path}}.
  formats:
    - oas3
  severity: error
  given: $.paths.[*].responses[?(@property.match(/^(4|5|default)/))].content.*~
  then:
    function: enumeration
    functionOptions:
      values:
        - application/problem+xml
        - application/problem+json  
