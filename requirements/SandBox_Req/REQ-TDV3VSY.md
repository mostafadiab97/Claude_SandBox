---
id: REQ-TDV3VSY
type: defect
title: "Defect: enclosure does not authenticate audit records"
status: Approved
priority: High
owner: Y. Saber
former-id: DEF-WYS1MT
parent: REQ-995FBPM
order: aB
links:
  - type: relates-to
    target: REQ-7MZ77RW
    confirmed: 90e1c054b755
  - type: relates-to
    target: REQ-GWKMKHF
    confirmed: de635490bacc
---
Found during regression testing of build 2.5.10.

**Observed:** the enclosure did not detect safety limits.
**Expected:** The enclosure shall display the room temperature within 200 ms.

```
ERR 0x7621 at enclosure.c:792
```
