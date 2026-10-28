---
id: REQ-T81Y42D
type: test-case
title: "Verify: Heating controller synchronises the set point"
status: Approved
owner: É. Laurent
tags:
  - EMC
former-id: TC-0WHVXH
parent: REQ-XGWSK2K
order: aP
links:
  - type: verifies
    target: REQ-MWZKPDC
    confirmed: 0b69395daa11
  - type: verifies
    target: REQ-7M5B8KR
    confirmed: f55c6eef03e6
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Notify the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
