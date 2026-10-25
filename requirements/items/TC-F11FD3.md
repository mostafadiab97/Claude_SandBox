---
id: TC-F11FD3
type: test-case
title: "Verify: Bluetooth LE link limits access tokens"
status: Review
priority: Medium
owner: H. Mostafa
parent: INFO-F0M7VC
order: 780
links:
  - type: verifies
    target: SYS-P934M9
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Synchronise relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
