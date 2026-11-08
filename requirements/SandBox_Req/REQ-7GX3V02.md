---
id: REQ-7GX3V02
type: test-case
title: "Verify: Main PCB limits sensor readings"
status: Review
owner: M. Farouk
tags:
  - release-1.0
  - ux
former-id: TC-43GJQ1
parent: REQ-F9Z1FYS
order: b0I
links:
  - type: verifies
    target: REQ-DCMQ8A6
    confirmed: a1bdacbc8613
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Log firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
