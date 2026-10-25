---
id: TC-6P7XYR
type: test-case
title: "Verify: Device registry authenticates user preferences"
status: Approved
priority: High
owner: N. Kamal
parent: INFO-7P4D8D
order: 1310
links:
  - type: verifies
    target: SYS-569DVN
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
