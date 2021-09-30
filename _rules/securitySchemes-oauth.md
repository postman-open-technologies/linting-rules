---
description: |-
  Json Web Tokens RFC7519 is a compact, URL-safe means of representing
  claims to be transferred between two parties. JWT can be enclosed in
  encrypted or signed tokens like JWS and JWE.
message: JWT usage should be detailed in `description` {{error}}.
given:
- $.[securitySchemes][?(@.type=="oauth2")]
then:
- field: description
  function: truthy
- field: description
  function: pattern
  functionOptions:
    match: .*RFC8725.*
...
description: |-
  Json Web Tokens RFC7519 is a compact, URL-safe means of representing
  claims to be transferred between two parties. JWT can be enclosed in
  encrypted or signed tokens like JWS and JWE.
message: JWT usage should be detailed in `description` {{error}}.
given:
- $.[securitySchemes][?(@.type=="oauth2")]
then:
- field: description
  function: truthy
- field: description
  function: pattern
  functionOptions:
    match: .*RFC8725.*