---
integer-format:
    x-tags:
        - it
        - RAC_REST_FORMAT_004
    description: >-
        Schema of type number or integer must specify a format to express the associated datatype, eg. `int32`, `int64`, You can express similar requirements using the `minimum` and `maximum` properties. See recommendation RAC_REST_FORMAT_004.
    message: Schema of type number or integer must specify a format. {{path}}
    formats:
        - oas3
    severity: error
    recommended: true
    given: |
        $.[?(@.type=="integer")]
    then:
        field: format
        function: truthy 
...
integer-format:
    x-tags:
        - it
        - RAC_REST_FORMAT_004
    description: >-
        Schema of type number or integer must specify a format to express the associated datatype, eg. `int32`, `int64`, You can express similar requirements using the `minimum` and `maximum` properties. See recommendation RAC_REST_FORMAT_004.
    message: Schema of type number or integer must specify a format. {{path}}
    formats:
        - oas3
    severity: error
    recommended: true
    given: |
        $.[?(@.type=="integer")]
    then:
        field: format
        function: truthy   