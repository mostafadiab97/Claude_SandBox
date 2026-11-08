---
id: REQ-ZH7P662
type: test-case
title: "Verify: Main PCB authenticates safety limits"
status: Review
priority: High
owner: H. Mostafa
former-id: TC-C700H7
parent: REQ-F9Z1FYS
order: b0s
links:
  - type: verifies
    target: REQ-0K8FF43
    confirmed: c4f0539f5269
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Measure humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
