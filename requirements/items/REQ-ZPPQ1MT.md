---
id: REQ-ZPPQ1MT
type: use-case
title: "UC: Synchronise the room temperature with the pairing process"
status: Obsolete
priority: Low
owner: J. Müller
former-id: UC-7XB15J
parent: REQ-X5TXBRB
order: aE
links:
  - type: relates-to
    target: REQ-W8GJYMQ
    confirmed: 30e7f07df0d1
---
**Actor:** home owner

**Main flow**
1. The user opens the pairing process.
2. The user changes energy consumption.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.
