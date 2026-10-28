---
id: TC-WFCPAH
type: test-case
title: "Verify: Cloud backend validates the room temperature"
status: Approved
priority: High
parent: INFO-7P4D8D
order: 20
links:
  - type: verifies
    target: SYS-XFVHXG
    confirmed: 6ba023b53f4f
  - type: verifies
    target: SW-2C9HYA
    confirmed: 4b4be5d0d1b1
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Validate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
