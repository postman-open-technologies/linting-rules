---
servers-use-https:
    x-tags:
        - security
    description: |-
        Servers must use https to ensure the origin of the responses
        and protect the integrity and the  confidentiality of the communication.

        You can use `http://` only on sandboxes environment.
        Use `x-sandbox: true` to skip this kind of check.
    message: "Non-sandbox url  {{value}} {{error}}. Add `x-sandbox: true` to skip
        this check on a specific server."
    given:
        - $.servers[?(@["x-sandbox"] != true)]
        - $.paths..servers[?(@["x-sandbox"] != true)]
    severity: error
    recommended: true
    then:
        field: url
        function: pattern
        functionOptions:
        match: ^https://.*  
...
servers-use-https:
    x-tags:
        - security
    description: |-
        Servers must use https to ensure the origin of the responses and protect the integrity and the  confidentiality of the communication. You can use `http://` only on sandboxes environment. Use `x-sandbox: true` to skip this kind of check.
    message: "Non-sandbox url  {{value}} {{error}}. Add `x-sandbox: true` to skip
        this check on a specific server."
    given:
        - $.servers[?(@["x-sandbox"] != true)]
        - $.paths..servers[?(@["x-sandbox"] != true)]
    severity: error
    recommended: true
    then:
        field: url
        function: pattern
        functionOptions:
        match: ^https://.* 