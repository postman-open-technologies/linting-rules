---
api-home-get:
    description: APIs root path MUST have a GET defined, otherwise people won't know how to get it.
    severity: warn
    given: $.paths[/]
    then:
        field: get
        function: truthy
...
api-home-get:
    description: APIs root path MUST have a GET defined, otherwise people won't know how to get it.
    severity: warn
    given: $.paths[/]
    then:
        field: get
        function: truthy