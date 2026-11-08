---
id: REQ-3VWVN2P
type: use-case
title: "UC: Detect the operating mode with the watchdog"
status: Draft
priority: Medium
owner: R. Nabil
former-id: UC-1JPC1B
parent: REQ-3EBQKRK
order: aE
links:
  - type: relates-to
    target: REQ-GCMD4T5
    confirmed: bcce6e51beb4
---
**Actor:** home owner

**Main flow**
1. The user opens the watchdog.
2. The user changes firmware images.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.
