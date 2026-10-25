---
id: TC-TPS5MK
type: test-case
title: "Verify: Bluetooth LE link detects access tokens"
status: Approved
priority: High
owner: M. Farouk
parent: INFO-F0M7VC
order: 790
links:
  - type: verifies
    target: SYS-2N03B4
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Store audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
