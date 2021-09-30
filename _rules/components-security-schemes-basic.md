---
components-security-schemes-basic:
    description: "Consider a more secure alternative to HTTP Basic."
    message: "HTTP Basic is a pretty insecure way to pass credentials around, please consider an alternative."
    severity: error
    given: $.components.securitySchemes[*]
    then:
        field: scheme
        function: pattern
        functionOptions:
        notMatch: basic 
...
components-security-schemes-basic:
    description: "Consider a more secure alternative to HTTP Basic."
    message: "HTTP Basic is a pretty insecure way to pass credentials around, please consider an alternative."
    severity: error
    given: $.components.securitySchemes[*]
    then:
        field: scheme
        function: pattern
        functionOptions:
        notMatch: basic 
