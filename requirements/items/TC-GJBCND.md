---
id: TC-GJBCND
type: test-case
title: "Verify: Bluetooth LE link reports sensor readings"
status: Review
priority: Medium
owner: محمد علي
parent: INFO-F0M7VC
order: 580
links:
  - type: verifies
    target: SYS-7RZPD7
  - type: verifies
    target: SW-JPCWP5
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Store firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
