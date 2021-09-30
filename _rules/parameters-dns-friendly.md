---
parameters-dns-friendly:
  severity: error
  description: Identifier parameter missing DNS-friendly pattern, e.g. ^[a-z0-9]([-a-z0-9]*[a-z0-9])?$
  given: $..parameters[?((@.name || '').match(/^id[ -_A-Z]|[ -_]id$|[a-z0-9]Id$/))]
  then:
    field: schema.pattern
    function: truthy
...
parameters-dns-friendly:
  severity: error
  description: Identifier parameter missing DNS-friendly pattern, e.g. ^[a-z0-9]([-a-z0-9]*[a-z0-9])?$
  given: $..parameters[?((@.name || '').match(/^id[ -_A-Z]|[ -_]id$|[a-z0-9]Id$/))]
  then:
    field: schema.pattern
    function: truthy