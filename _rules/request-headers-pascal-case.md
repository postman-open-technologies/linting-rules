---
request-headers-pascal-case:
    x-tags:
        - it
    description: |
        Headers should be pascal-case.

        See Italian recommendation RAC_REST_NAME_003.
    message: "{{value}} {{error}} in {{path}}"
    severity: hint
    recommended: true
    given:
        - $.[parameters][?(@.in=="header")].name
    then:
        function: casing
        functionOptions:
            type: pascal
            separator:
                char: "-"
...
request-headers-pascal-case:
    x-tags:
        - it
    description: |
        Headers should be pascal-case.

        See Italian recommendation RAC_REST_NAME_003.
    message: "{{value}} {{error}} in {{path}}"
    severity: hint
    recommended: true
    given:
        - $.[parameters][?(@.in=="header")].name
    then:
        function: casing
        functionOptions:
        type: pascal
        separator:
            char: "-" 