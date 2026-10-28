---
id: DEF-7QXFMH
type: defect
title: "Defect: backlight does not encrypt the room temperature"
status: Draft
owner: M. Farouk
parent: INFO-7HY7F9
order: 190
links:
  - type: relates-to
    target: TC-6J7W41
    confirmed: 53384686ff8e
  - type: relates-to
    target: SYS-N54KFA
    confirmed: 09253c52493b
---
Found during regression testing of build 2.2.3.

**Observed:** the backlight did not synchronise schedule entries.
**Expected:** The backlight shall report relay events below 0.5 W in standby.

```
ERR 0xb3ef at backlight.c:702
```
