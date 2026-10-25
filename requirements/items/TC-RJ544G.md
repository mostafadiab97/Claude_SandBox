---
id: TC-RJ544G
type: test-case
title: "Verify: Device registry detects humidity values"
status: Review
priority: Medium
owner: Y. Saber
parent: INFO-7P4D8D
order: 920
links:
  - type: verifies
    target: SYS-AP48M6
  - type: verifies
    target: SW-D7YQPY
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Encrypt relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
