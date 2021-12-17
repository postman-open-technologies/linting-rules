---
swagger-v2-version-segment-second:
  description: Ensuring the second path segment is a version like v1.
  message: The second path segment should be the version.
  given: $.paths
  then:
    field: '@key'
    function: pattern
    functionOptions:
      match: ^/[^/]+/v\d+/.+$
...
swagger-v2-version-segment-second:
  description: Ensuring the second path segment is a version like v1.
  message: The second path segment should be the version.
  given: $.paths
  then:
    field: '@key'
    function: pattern
    functionOptions:
      match: ^/[^/]+/v\d+/.+$
