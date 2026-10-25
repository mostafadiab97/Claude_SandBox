---
id: UC-SKMAVP
type: use-case
title: "UC: Report the connection state with the main PCB"
status: Approved
owner: H. Mostafa
parent: INFO-6W132E
order: 130
links:
  - type: relates-to
    target: STK-CDR1Y9
---
**Actor:** home owner

**Main flow**
1. The user opens the main PCB.
2. The user changes safety limits.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.
