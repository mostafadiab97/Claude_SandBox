---
id: REQ-BW7MDFP
type: test-case
title: "Verify: Heat pump driver restores error conditions"
status: Draft
priority: Medium
owner: J. Müller
former-id: TC-Z3VV6X
parent: REQ-XGWSK2K
order: ak
links:
  - type: verifies
    target: REQ-BFGS1K4
    confirmed: b0286a82c3c7
  - type: verifies
    target: REQ-G6XE2MB
    confirmed: 999f2b19f22a
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
