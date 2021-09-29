---
description: "Se limita el uso de las siguientes palabras que deber\xE1n obviarse
  en la redacci\xF3n del contrato."
severity: warn
message: 'CONT09: Invalid property value: {{value}} (expected: Please, review application
  black list.).'
recommended: true
resolved: false
given:
- $.info..description
- $.paths..description
- $.parameters..description
- $.definitions..description
- $.info..title
- $.info..name
- $.tags..name
- $.parameters..name
- $.paths..summary
- $.paths..operationId
then:
  function: pattern
  functionOptions:
    notMatch: \b(cangrejo|bob|esponja)\b
...description: "Se limita el uso de las siguientes palabras que deber\xE1n obviarse
  en la redacci\xF3n del contrato."
severity: warn
message: 'CONT09: Invalid property value: {{value}} (expected: Please, review application
  black list.).'
recommended: true
resolved: false
given:
- $.info..description
- $.paths..description
- $.parameters..description
- $.definitions..description
- $.info..title
- $.info..name
- $.tags..name
- $.parameters..name
- $.paths..summary
- $.paths..operationId
then:
  function: pattern
  functionOptions:
    notMatch: \b(cangrejo|bob|esponja)\b