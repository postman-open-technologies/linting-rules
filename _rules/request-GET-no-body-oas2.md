---
request-GET-no-body-oas2:
    description: A `GET` request MUST NOT accept a `body` parameter
    severity: error
    format: [oas2]
    given: $.paths..get.parameters..in
    then:
        function: pattern
        functionOptions:
        notMatch: "/^body$/"  
    x-status: draft
    x-tags:
        - Tag             
...
request-GET-no-body-oas2:
    description: A `GET` request MUST NOT accept a `body` parameter
    severity: error
    format: [oas2]
    given: $.paths..get.parameters..in
    then:
        function: pattern
        functionOptions:
        notMatch: "/^body$/"  
    x-status: draft
    x-tags:
        - Tag           