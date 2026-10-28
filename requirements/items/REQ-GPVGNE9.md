---
id: DEF-MWPR7V
type: defect
title: "Defect: OTA server does not notify access tokens"
status: Approved
priority: Low
owner: محمد علي
parent: INFO-M91889
order: 40
links:
  - type: relates-to
    target: TC-GX7NG7
    confirmed: 1f75e64a55a1
  - type: relates-to
    target: SYS-5N0YKT
    confirmed: 08567b44affd
---
Found during regression testing of build 2.2.12.

**Observed:** the OTA server did not validate the connection state.
**Expected:** The OTA server shall validate access tokens after a power loss.

```
ERR 0xf192 at OTA_server.c:671
```
