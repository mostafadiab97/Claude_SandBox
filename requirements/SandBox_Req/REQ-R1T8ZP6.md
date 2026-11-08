---
id: REQ-R1T8ZP6
type: defect
title: "Defect: battery backup does not log audit records"
status: Draft
owner: H. Mostafa
former-id: DEF-2QAP2T
parent: REQ-995FBPM
order: a0
links:
  - type: relates-to
    target: REQ-K0MQQGN
    confirmed: 66c1ae986d92
  - type: relates-to
    target: REQ-Q01BYF2
    confirmed: 07a6530c6e8f
---
Found during regression testing of build 2.5.9.

**Observed:** the battery backup did not store the connection state.
**Expected:** The battery backup shall validate humidity values for at least 10 years.

```
ERR 0x5d01 at battery_backup.c:513
```
