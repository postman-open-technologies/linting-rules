---
swagger-v2-schema-additional-properties:
  description: Restricts objects from having additional properties defined.
  message: All schema objects should have additionalProperties set to false.
  formats:
    - oas2
  severity: warn
  recommended: true
  given:
    - >-
      $.[?(@.type=="object" && @.additionalProperties &&
      @.additionalProperties!=true && @.additionalProperties!=false )]
  then:
    - field: maxProperties
      function: defined
...
swagger-v2-schema-additional-properties:
  description: Restricts objects from having additional properties defined.
  message: All schema objects should have additionalProperties set to false.
  formats:
    - oas2
  severity: warn
  recommended: true
  given:
    - >-
      $.[?(@.type=="object" && @.additionalProperties &&
      @.additionalProperties!=true && @.additionalProperties!=false )]
  then:
    - field: maxProperties
      function: defined
