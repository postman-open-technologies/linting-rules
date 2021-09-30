---
response-headers-pascal-case:
    x-tags:
        - it
    description: |
        Headers should be pascal-case.

        See Italian recommendation RAC_REST_NAME_003.
    message: "Header {{error}}: {{path}}"
    severity: hint
    recommended: true
    given:
        - $.[responses][*].headers.*~
    then:
        function: casing
        functionOptions:
        type: pascal
        separator:
            char: "-"     
...
response-headers-pascal-case:
    x-tags:
        - it
    description: |
        Headers should be pascal-case.

        See Italian recommendation RAC_REST_NAME_003.
    message: "Header {{error}}: {{path}}"
    severity: hint
    recommended: true
    given:
        - $.[responses][*].headers.*~
    then:
        function: casing
        functionOptions:
        type: pascal
        separator:
            char: "-" 