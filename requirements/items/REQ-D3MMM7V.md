---
id: TC-1XKN4K
type: test-case
title: "Verify: Zigbee radio synchronises the connection state"
status: Approved
owner: محمد علي
parent: INFO-F0M7VC
order: 450
links:
  - type: verifies
    target: SYS-RB6KMZ
    confirmed: 9e9699c7ff42
  - type: verifies
    target: SW-CT0KF3
    confirmed: b023bd0bf70c
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Log audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
