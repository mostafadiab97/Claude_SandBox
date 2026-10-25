---
id: TC-SXVMX3
type: test-case
title: "Verify: Bluetooth LE link reports the room temperature"
status: Review
priority: Low
owner: محمد علي
parent: INFO-F0M7VC
order: 190
links:
  - type: verifies
    target: SYS-PX6WZT
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Log energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
