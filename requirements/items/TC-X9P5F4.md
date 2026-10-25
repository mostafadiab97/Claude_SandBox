---
id: TC-X9P5F4
type: test-case
title: "Verify: Zigbee radio measures the operating mode"
status: Approved
priority: Medium
parent: INFO-F0M7VC
order: 1460
links:
  - type: verifies
    target: SYS-SPX676
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
