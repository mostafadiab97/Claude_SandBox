---
id: TC-SDRMF5
type: test-case
title: "Verify: Zigbee radio notifys the room temperature"
status: Approved
priority: High
parent: INFO-F0M7VC
order: 1350
links:
  - type: verifies
    target: SYS-DT07VH
  - type: verifies
    target: SW-7XG01T
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Measure error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
