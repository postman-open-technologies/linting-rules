---
tags-name:
    description: "Tags must have a name."
    given: $.tags[*]
    severity: error
    then:
        field: name
        function: truthy  
    x-status: draft
    x-tags:
        - Tags     
...
tags-name:
    description: "Tags must have a name."
    given: $.tags[*]
    severity: error
    then:
        field: name
        function: truthy  
    x-status: draft
    x-tags:
        - Tags