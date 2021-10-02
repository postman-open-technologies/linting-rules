---
paths-kebab-case:
    description: Should paths be kebab-case.
    message: '{{property}} should be kebab-case (lower case and separated with hyphens)'
    severity: warn
    given: $.paths[*]~
    then:
        function: pattern
        functionOptions:
        match: "^(\/|[a-z0-9-.]+|{[a-zA-Z0-9_]+})+$" 
        #match: ^\/([a-z0-9]+(-[a-z0-9]+)*)?(\/[a-z0-9]+(-[a-z0-9]+)*|\/{.+})*$
    x-status: draft
    x-tags:
        - Tag         
...
paths-kebab-case:
    description: Should paths be kebab-case.
    message: '{{property}} should be kebab-case (lower case and separated with hyphens)'
    severity: warn
    given: $.paths[*]~
    then:
        function: pattern
        functionOptions:
        match: "^(\/|[a-z0-9-.]+|{[a-zA-Z0-9_]+})+$" 
    x-status: draft
    x-tags:
        - Tag              