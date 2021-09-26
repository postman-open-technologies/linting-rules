---
unknown-error-format:
    description: "Every error response SHOULD support either RFC 7807 (https://tools.ietf.org/html/rfc6648) or the JSON:API Error format."
    formats: [oas3]
    severity: warn
    given: $.paths.[*].responses[?(@property.match(/^(4|5)/))].content.*~
    then:
        function: enumeration
        functionOptions:
        values:
        - application/vnd.api+json
        - application/problem+xml
        - application/problem+json    
...
unknown-error-format:
    description: "Every error response SHOULD support either RFC 7807 (https://tools.ietf.org/html/rfc6648) or the JSON:API Error format."
    formats: [oas3]
    severity: warn
    given: $.paths.[*].responses[?(@property.match(/^(4|5)/))].content.*~
    then:
        function: enumeration
        functionOptions:
        values:
        - application/vnd.api+json
        - application/problem+xml
        - application/problem+json 