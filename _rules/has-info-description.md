---
has-info-description:
    x-tags:
        - metadata
    description: "API must have description #/info/description"
    given: $
    severity: error
    recommended: true
    type: style
    formats:
        - oas3
    then:
        field: info.description
        function: truthy    
...
has-info-description:
    x-tags:
        - metadata
    description: "API must have description #/info/description"
    given: $
    severity: error
    recommended: true
    type: style
    formats:
        - oas3
    then:
        field: info.description
        function: truthy  
