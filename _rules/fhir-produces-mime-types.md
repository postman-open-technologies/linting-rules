---
description: FHIR mime-type must be application/fhir+(xml|json|turtle)
severity: error
recommended: true
format: oas2
given: $..produces.*
then:
  function: schema
  functionOptions:
    schema:
      type: string
      enum:
      - application/fhir+xml
      - application/fhir+json
      - application/fhir+turtle
...description: FHIR mime-type must be application/fhir+(xml|json|turtle)
severity: error
recommended: true
format: oas2
given: $..produces.*
then:
  function: schema
  functionOptions:
    schema:
      type: string
      enum:
      - application/fhir+xml
      - application/fhir+json
      - application/fhir+turtle