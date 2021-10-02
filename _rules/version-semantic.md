---
version-semantic:
    description: >-
        The API version field should follow

        [semantic versioning](https://semver.org/#semantic-versioning-specification-semver).
    severity: error
    recommended: true
    message: Specs should follow semantic versioning. {{value}} is not a valid version.
    given: $.info.version
    then:
        function: pattern
        functionOptions:
        match: ^[0-9]+.[0-9]+.[0-9]+(-[a-z0-9+.-]+)?   
    x-status: draft
    x-tags:
        - Tag         
...
version-semantic:
    description: >-
        The API version field should follow

        [semantic versioning](https://semver.org/#semantic-versioning-specification-semver).
    severity: error
    recommended: true
    message: Specs should follow semantic versioning. {{value}} is not a valid version.
    given: $.info.version
    then:
        function: pattern
        functionOptions:
        match: ^[0-9]+.[0-9]+.[0-9]+(-[a-z0-9+.-]+)?   
    x-status: draft
    x-tags:
        - Tag 
