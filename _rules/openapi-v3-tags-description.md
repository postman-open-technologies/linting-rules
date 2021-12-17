---
openapi-v3-tags-description:
  description: Ensuring that all tags have a description.
  message: All tags should have a description.
  given: $.tags[*]
  severity: error
  then:
    field: description
    function: truthy
...
openapi-v3-tags-description:
  description: Ensuring that all tags have a description.
  message: All tags should have a description.
  given: $.tags[*]
  severity: error
  then:
    field: description
    function: truthy
