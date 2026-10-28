---
id: REQ-J516ZSS
type: defect
title: "Defect: watchdog does not display schedule entries"
status: Approved
priority: Medium
owner: N. Kamal
former-id: DEF-91SS6T
parent: REQ-1XKBKFE
order: aD
links:
  - type: relates-to
    target: REQ-KV3QY0R
    confirmed: ac91d772d1f9
  - type: relates-to
    target: REQ-WQ6EFZQ
    confirmed: 70d3053751d1
---
Found during regression testing of build 2.8.25.

**Observed:** the watchdog did not display user preferences.
**Expected:** The watchdog shall validate sensor readings without user interaction.

```
ERR 0x8ade at watchdog.c:861
```
