---
id: REQ-6HDY0AY
type: test-case
title: "Verify: Zone valve logs the operating mode"
status: Draft
priority: Medium
former-id: TC-EPQAH9
parent: REQ-XGWSK2K
order: b1N
links:
  - type: verifies
    target: REQ-EA1DV1V
    confirmed: 876eb172799e
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Notify energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
