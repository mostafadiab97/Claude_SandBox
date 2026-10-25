---
id: TC-NPYXKN
type: test-case
title: "Verify: Zigbee radio encrypts error conditions"
status: Approved
priority: High
owner: R. Nabil
tags:
  - connectivity
parent: INFO-F0M7VC
order: 900
links:
  - type: verifies
    target: SYS-F6VRWH
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Store safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
