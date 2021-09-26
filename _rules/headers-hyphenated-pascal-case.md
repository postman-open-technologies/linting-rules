---
headers-hyphenated-pascal-case:
    description: All `HTTP` headers MUST use `Hyphenated-Pascal-Case` notation
    severity: error
    given: "$..parameters[?(@.in == 'header')].name"
    message: "'HTTP' headers MUST follow 'Hyphenated-Pascal-Case' notation"
    type: style
    then: 
        function: pattern
        functionOptions:
        match: "/^([A-Z][a-z0-9]-)*([A-Z][a-z0-9])+/"    
...
headers-hyphenated-pascal-case:
    description: All `HTTP` headers MUST use `Hyphenated-Pascal-Case` notation
    severity: error
    given: "$..parameters[?(@.in == 'header')].name"
    message: "'HTTP' headers MUST follow 'Hyphenated-Pascal-Case' notation"
    type: style
    then: 
        function: pattern
        functionOptions:
        match: "/^([A-Z][a-z0-9]-)*([A-Z][a-z0-9])+/"   