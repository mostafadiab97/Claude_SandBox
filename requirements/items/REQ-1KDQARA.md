---
id: REQ-1KDQARA
type: test-case
title: "Verify: Regulation loop limits sensor readings"
status: Review
priority: Medium
owner: L. Samir
tags:
  - release-1.0
former-id: TC-FY5MVC
parent: REQ-XGWSK2K
order: aQ
links:
  - type: verifies
    target: REQ-3NYYTRF
    confirmed: daa058155ad3
  - type: verifies
    target: REQ-4AGJ55F
    confirmed: f757c2d54080
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Calibrate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
