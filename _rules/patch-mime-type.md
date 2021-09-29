---
description: PATCH operations must use JSON Patch and/or JSON Merge Patch with the
  correct MIME type.
given: $..paths..patch.requestBody.content
then:
  field: '@key'
  function: pattern
  functionOptions:
    match: ^application\/(json|merge)-patch\+json$
...description: PATCH operations must use JSON Patch and/or JSON Merge Patch with the
  correct MIME type.
given: $..paths..patch.requestBody.content
then:
  field: '@key'
  function: pattern
  functionOptions:
    match: ^application\/(json|merge)-patch\+json$