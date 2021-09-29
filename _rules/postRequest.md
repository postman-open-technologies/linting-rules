---
description: Must have a 201 response
message: Post requests should have a 201 response, please add it for {{path}}.
recommended: true
type: style
given: $..post.responses
severity: warn
resolved: false
then:
- field: "201"
  function: truthy
...description: Must have a 201 response
message: Post requests should have a 201 response, please add it for {{path}}.
recommended: true
type: style
given: $..post.responses
severity: warn
resolved: false
then:
- field: "201"
  function: truthy