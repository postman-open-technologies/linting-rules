---
parameter-description:
    description: Parameters must have a description.
    recommended: true
    given: $..properties.*
    then:
        field: description
        function: truthy
    x-status: draft
    x-tags:
        - Tag            
...
parameter-description:
    description: Parameters must have a description.
    recommended: true
    given: $..properties.*
    then:
        field: description
        function: truthy
    x-status: draft
    x-tags:
        - Tag             
