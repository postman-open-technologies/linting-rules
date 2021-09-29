---
description: Contact should have `name` and `url` properties.
given: $.info.contact
then:
- field: name
  function: truthy
- field: url
  function: truthy
...description: Contact should have `name` and `url` properties.
given: $.info.contact
then:
- field: name
  function: truthy
- field: url
  function: truthy