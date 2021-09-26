---
servers-description:
    x-tags:
        - metadata
        - it
    description: "Servers must have a description."
    given:
        - $.servers[*]
        - $.paths..servers
    severity: error
    then:
        field: description
        function: truthy    
...
servers-description:
    x-tags:
        - metadata
        - it
    description: Servers must have a description.
    given:
        - $.servers[*]
        - $.paths..servers
    severity: error
    then:
        field: description
        function: truthy  