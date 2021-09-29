---
description: Path should contain only recommended characters.
message: Path contains non-recommended characters.
severity: hint
formats:
- oas2
- oas3
given: $.paths.*~
then:
  function: pattern
  functionOptions:
    match: ^(/([0-9A-Za-z._~-]+|{[^}]+}))*(/([0-9A-Za-z._~:-]+|{[^}]*}(:[0-9A-Za-z._~-]+)?))$
...
message: Path contains non-recommended characters.
severity: hint
formats:
- oas2
- oas3
given: $.paths.*~
then:
  function: pattern
  functionOptions:
    match: ^(/([0-9A-Za-z._~-]+|{[^}]+}))*(/([0-9A-Za-z._~:-]+|{[^}]*}(:[0-9A-Za-z._~-]+)?))$