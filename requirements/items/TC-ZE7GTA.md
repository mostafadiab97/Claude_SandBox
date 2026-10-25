---
id: TC-ZE7GTA
type: test-case
title: "Verify: Zigbee radio displays safety limits"
status: Approved
priority: Medium
owner: K. Tanaka
parent: INFO-F0M7VC
order: 140
links:
  - type: verifies
    target: SYS-GDH96C
  - type: verifies
    target: SW-H71N1T
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Measure safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
