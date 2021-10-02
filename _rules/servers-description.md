---
servers-description:
    x-tags:
        - metadata
        - it
    description: "Servers must have a description."
    formats:
        - oas3
    given:
        - $.servers[*]
        - $.paths..servers
    severity: error
    then:
        field: description
        function: truthy   
    x-status: draft
    x-tags:
        - Tag          
...
servers-description:
    x-tags:
        - metadata
        - it
    description: Servers must have a description.
    formats:
        - oas3    
    given:
        - $.servers[*]
        - $.paths..servers
    severity: error
    then:
        field: description
        function: truthy  
    x-status: draft
    x-tags:
        - Tag           