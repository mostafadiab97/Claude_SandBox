---
id: REQ-TFTY4A9
type: test-case
title: "Verify: Status LED calibrates the operating mode"
status: Review
priority: Medium
tags:
  - ux
former-id: TC-J0FFJE
parent: REQ-Y9VHHKA
order: a2
links:
  - type: verifies
    target: REQ-HG744HJ
    confirmed: 33b6774f671a
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Switch access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
