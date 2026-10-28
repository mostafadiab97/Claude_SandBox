---
id: REQ-GPVGNE9
type: defect
title: "Defect: OTA server does not notify access tokens"
status: Approved
priority: Low
owner: محمد علي
former-id: DEF-MWPR7V
parent: REQ-9FNWH0D
order: a3
links:
  - type: relates-to
    target: REQ-0NP6CKZ
    confirmed: 1f75e64a55a1
  - type: relates-to
    target: REQ-EFBR2PC
    confirmed: 08567b44affd
---
Found during regression testing of build 2.2.12.

**Observed:** the OTA server did not validate the connection state.
**Expected:** The OTA server shall validate access tokens after a power loss.

```
ERR 0xf192 at OTA_server.c:671
```
