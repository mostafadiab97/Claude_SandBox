---
id: DEF-2QAP2T
type: defect
title: "Defect: battery backup does not log audit records"
status: Draft
owner: H. Mostafa
parent: INFO-BB7M2N
order: 10
links:
  - type: relates-to
    target: TC-Y0QTD7
  - type: relates-to
    target: SYS-FMNTZ0
---
Found during regression testing of build 2.5.9.

**Observed:** the battery backup did not store the connection state.
**Expected:** The battery backup shall validate humidity values for at least 10 years.

```
ERR 0x5d01 at battery_backup.c:513
```
