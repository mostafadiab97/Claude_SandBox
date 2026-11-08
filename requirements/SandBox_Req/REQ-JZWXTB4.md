---
id: REQ-JZWXTB4
type: test-case
title: "Verify: Watchdog reports the connection state"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - release-1.0
former-id: TC-KMSMJY
parent: REQ-K6FGAY0
order: b0v
links:
  - type: verifies
    target: REQ-1NZ47K3
    confirmed: 6d6c12313a2b
  - type: verifies
    target: REQ-W191KF9
    confirmed: 63cf0f5701dc
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Validate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
