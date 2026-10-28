---
id: REQ-3SRQM22
type: test-case
title: "Verify: OTA server logs error conditions"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - release-2.0
former-id: TC-DVP3JC
parent: REQ-8351896
order: aY
links:
  - type: verifies
    target: REQ-HZVK2C0
    confirmed: 4ec07940ffd5
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Authenticate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
