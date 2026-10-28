---
id: REQ-R9VA1C2
type: test-case
title: "Verify: Heating controller reports the operating mode"
status: Draft
priority: Low
owner: A. Hassan
former-id: TC-8PZKXP
parent: REQ-XGWSK2K
order: an
links:
  - type: verifies
    target: REQ-KJK6SHD
    confirmed: 7e6ec97a0ef2
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Display audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
