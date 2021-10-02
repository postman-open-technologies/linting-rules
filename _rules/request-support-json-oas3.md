---
request-support-json-oas3:
    description: Every request SHOULD support `application/json` media type
    formats: [oas3]
    severity: warn
    message: "{{description}}: {{error}}"
    given: $.paths.[*].requestBody.content[?(@property.indexOf('json') === -1)]^
    then:
        function: falsy
    x-status: draft
    x-tags:
        - Tag            
...
request-support-json-oas3:
    description: Every request SHOULD support `application/json` media type
    formats: [oas3]
    severity: warn
    message: "{{description}}: {{error}}"
    given: $.paths.[*].requestBody.content[?(@property.indexOf('json') === -1)]^
    then:
        function: falsy
    x-status: draft
    x-tags:
        - Tag                    