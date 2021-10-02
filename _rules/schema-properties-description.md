---
parameter-description:
    description: Parameters must have a description.
    recommended: true
    given: $..properties.*
    then:
        field: description
        function: truthy
...
parameter-description:
    description: Parameters must have a description.
    recommended: true
    given: $..properties.*
    then:
        field: description
        function: truthy
