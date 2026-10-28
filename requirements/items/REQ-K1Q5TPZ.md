---
id: TC-E55T3C
type: test-case
title: "Verify: Relay board notifys relay events"
status: Draft
priority: Low
owner: N. Kamal
parent: INFO-MACGC3
order: 790
links:
  - type: verifies
    target: SYS-3V07ZT
    confirmed: bd35bc218b6c
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Notify access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
