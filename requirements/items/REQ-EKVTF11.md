---
id: REQ-EKVTF11
type: test-case
title: "Verify: Heating controller reports the connection state"
status: Review
priority: Medium
owner: S. Adel
former-id: TC-RYMG64
parent: REQ-XGWSK2K
order: ax
links:
  - type: verifies
    target: REQ-E16RF9X
    confirmed: cf6a8acfb8a2
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Store relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
