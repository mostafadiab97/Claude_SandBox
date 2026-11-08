---
id: REQ-EBVV9S2
type: defect
title: "Defect: boiler interface does not limit firmware images"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - connectivity
former-id: DEF-FCD2R1
parent: REQ-XJDN42Y
order: a2
links:
  - type: relates-to
    target: REQ-7B39TZ9
    confirmed: 1b958c991b13
  - type: relates-to
    target: REQ-QWGMBHE
    confirmed: de721eeebf34
---
Found during regression testing of build 2.8.37.

**Observed:** the boiler interface did not report user preferences.
**Expected:** The boiler interface shall measure the connection state without user interaction.

```
ERR 0x0902 at boiler_interface.c:717
```
