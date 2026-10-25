---
id: TC-6RW9BP
type: test-case
title: "Verify: Bluetooth LE link detects user preferences"
status: Approved
priority: Medium
owner: A. Hassan
parent: INFO-F0M7VC
order: 980
links:
  - type: verifies
    target: SYS-MA8PA2
  - type: verifies
    target: SW-E6A04Q
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
