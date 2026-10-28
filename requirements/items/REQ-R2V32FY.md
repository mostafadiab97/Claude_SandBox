---
id: REQ-R2V32FY
type: test-case
title: "Verify: Power supply logs the room temperature"
status: Approved
priority: Medium
owner: محمد علي
former-id: TC-EBBTG7
parent: REQ-F9Z1FYS
order: ae
links:
  - type: verifies
    target: REQ-222GKXF
    confirmed: 5bdb17b664f3
  - type: verifies
    target: REQ-P7GSJF8
    confirmed: 61e860ae008f
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Measure safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
