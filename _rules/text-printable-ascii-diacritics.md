---
description: Text MUST be printable ASCII or diacritics. [ASCII table](https://theasciicode.com.ar/)
message: '{{property}}: ''{{value}}'' {{error}}'
recommended: true
resolved: false
type: style
severity: error
given: $..[description,summary,title]
then:
  function: pattern
  functionOptions:
    match: "^[\\s!-/0-9:-@A-Z[-`a-z{-~\xE1\xE9\xED\xF3\xFA\xE4\xEB\xEF\xF6\xFC\xE0\xE8\xEC\xF2\xF9\xF1\xE7]+$"
...description: Text MUST be printable ASCII or diacritics. [ASCII table](https://theasciicode.com.ar/)
message: '{{property}}: ''{{value}}'' {{error}}'
recommended: true
resolved: false
type: style
severity: error
given: $..[description,summary,title]
then:
  function: pattern
  functionOptions:
    match: "^[\\s!-/0-9:-@A-Z[-`a-z{-~\xE1\xE9\xED\xF3\xFA\xE4\xEB\xEF\xF6\xFC\xE0\xE8\xEC\xF2\xF9\xF1\xE7]+$"