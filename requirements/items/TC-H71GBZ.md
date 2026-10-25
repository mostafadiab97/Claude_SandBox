---
id: TC-H71GBZ
type: test-case
title: "Verify: Device registry notifys sensor readings"
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - accessibility
  - power
  - safety
parent: INFO-7P4D8D
order: 1540
links:
  - type: verifies
    target: SYS-SASG4P
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Display energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
