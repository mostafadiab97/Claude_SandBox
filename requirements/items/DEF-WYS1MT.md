---
id: DEF-WYS1MT
type: defect
title: "Defect: enclosure does not authenticate audit records"
status: Approved
priority: High
owner: Y. Saber
parent: INFO-BB7M2N
order: 120
links:
  - type: relates-to
    target: TC-XJAF7S
    confirmed: 90e1c054b755
  - type: relates-to
    target: SYS-FN6K6C
    confirmed: de635490bacc
---
Found during regression testing of build 2.5.10.

**Observed:** the enclosure did not detect safety limits.
**Expected:** The enclosure shall display the room temperature within 200 ms.

```
ERR 0x7621 at enclosure.c:792
```
