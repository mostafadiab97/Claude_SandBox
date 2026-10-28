---
id: TC-0BHR49
type: test-case
title: "Verify: Device registry validates the connection state"
status: Approved
priority: Medium
owner: محمد علي
tags:
  - connectivity
parent: INFO-7P4D8D
order: 620
links:
  - type: verifies
    target: SYS-BQ9NSH
    confirmed: e9c956142786
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Restore relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
