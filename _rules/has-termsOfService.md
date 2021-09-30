---
has-termsOfService:
    x-tags:
        - metadata
    message: "API MUST reference the URL of the Terms of Service  in
        #/info/termsOfService."
    description: API MUST reference the URL of the Terms of Service  in
        `#/info/termsOfService`
    given: $
    severity: error
    recommended: true
    type: style
    formats:
        - oas3
    then:
        field: info.termsOfService
        function: truthy    
...
has-termsOfService:
    x-tags:
        - metadata
    message: "API MUST reference the URL of the Terms of Service  in
        #/info/termsOfService."
    description: API MUST reference the URL of the Terms of Service  in
        `#/info/termsOfService`
    given: $
    severity: error
    recommended: true
    type: style
    formats:
        - oas3
    then:
        field: info.termsOfService
        function: truthy  