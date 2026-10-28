---
id: REQ-KNB05EJ
type: test-case
title: "Verify: Heat pump driver validates the connection state"
status: Review
priority: Medium
owner: محمد علي
former-id: TC-CT7VNP
parent: REQ-XGWSK2K
order: aA
links:
  - type: verifies
    target: REQ-7EANCXE
    confirmed: c02f405b6878
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Switch access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
