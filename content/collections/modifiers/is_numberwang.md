---
id: f3e9d043-ff25-4778-9915-0cfafc52e166
blueprint: modifiers
modifier_types:
  - string
  - conditions
title: 'Is Numberwang'
---
Is it or is it not numberwang? Returns `true` if it is indeed numberwang.

```yaml
number: 1002
```

::tabs

::tab antlers
```antlers
{{ if number | is_numberwang }}
```
::tab blade
```blade
@if (Statamic::modify($number)->isNumberwang()->fetch()) ... @endif
```
::

```html
???
```
