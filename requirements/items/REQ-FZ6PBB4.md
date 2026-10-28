---
id: REQ-FZ6PBB4
type: defect
title: "Defect: local API does not switch energy consumption"
status: Approved
priority: High
owner: M. Farouk
tags:
  - release-1.0
former-id: DEF-NV62BS
parent: REQ-YW554H8
order: a1
links:
  - type: relates-to
    target: REQ-73AGMH5
    confirmed: 4b17aa37c283
  - type: relates-to
    target: REQ-BNSVZ8R
    confirmed: b3432a56f6cd
---
Found during regression testing of build 2.3.27.

**Observed:** the local API did not restore safety limits.
**Expected:** The local API shall display the room temperature after a power loss.

```
ERR 0xc453 at local_API.c:532
```
