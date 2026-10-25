---
id: TC-NG6T88
type: test-case
title: "Verify: Device registry authenticates humidity values"
status: Draft
priority: High
owner: A. Hassan
parent: INFO-7P4D8D
order: 1520
links:
  - type: verifies
    target: SYS-6892JV
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Detect the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
