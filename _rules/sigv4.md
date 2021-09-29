---
severity: error
recommended: true
message: Specs should enable awsSigv4 in securitySchemes.sigv4. {{value}} is not a
  valid version.
given: $..components.securitySchemes.sigv4.x-amazon-apigateway-authtype
then:
  function: pattern
  functionOptions:
    match: ^awsSigv4$
...severity: error
recommended: true
message: Specs should enable awsSigv4 in securitySchemes.sigv4. {{value}} is not a
  valid version.
given: $..components.securitySchemes.sigv4.x-amazon-apigateway-authtype
then:
  function: pattern
  functionOptions:
    match: ^awsSigv4$