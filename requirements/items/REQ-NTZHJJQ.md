---
id: REQ-NTZHJJQ
type: test-case
title: "Verify: Cloud backend limits relay events"
status: Approved
priority: High
owner: محمد علي
former-id: TC-9VFD4X
parent: REQ-8351896
order: ae
links:
  - type: verifies
    target: REQ-BNDJJ01
    confirmed: fa525e92566c
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Calibrate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
