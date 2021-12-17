---
openapi-v3-tags-name:
  description: Ensuring that all tags have a name.
  message: All tags should have a name.
  given: $.tags[*]
  severity: error
  then:
    field: name
    function: truthy
...
openapi-v3-tags-name:
  description: Ensuring that all tags have a name.
  message: All tags should have a name.
  given: $.tags[*]
  severity: error
  then:
    field: name
    function: truthy
