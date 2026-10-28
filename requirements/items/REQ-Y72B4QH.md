---
id: REQ-Y72B4QH
type: use-case
title: "UC: Report the connection state with the main PCB"
status: Approved
owner: H. Mostafa
former-id: UC-SKMAVP
parent: REQ-QV7VW2A
order: aC
links:
  - type: relates-to
    target: REQ-QC1Z78M
    confirmed: d9857f8b33bf
---
**Actor:** home owner

**Main flow**
1. The user opens the main PCB.
2. The user changes safety limits.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.
