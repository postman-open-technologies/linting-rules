---
paths-status-return-problem:
    x-tags:
        - it
    description: '"/status" must return a Problem object.'
    message: "{{error}}"
    severity: error
    recommended: true
    given: $.paths.'/status'.get.responses.200.content.*~
    then:
        function: enumeration
        functionOptions:
        values:
            - application/problem+xml
            - application/problem+json   
...
paths-status-return-problem:
    x-tags:
        - it
    description: '"/status" must return a Problem object.'
    message: "{{error}}"
    severity: error
    recommended: true
    given: $.paths.'/status'.get.responses.200.content.*~
    then:
        function: enumeration
        functionOptions:
        values:
            - application/problem+xml
            - application/problem+json    