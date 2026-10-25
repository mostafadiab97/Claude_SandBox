---
id: TC-YD0DAF
type: test-case
title: "Verify: Zigbee radio reports sensor readings"
status: Approved
priority: Medium
parent: INFO-F0M7VC
order: 740
links:
  - type: verifies
    target: SYS-1KYW4V
    confirmed: b5edec3ba8f3
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
