---
id: REQ-ZYA7RFM
type: test-case
title: "Verify: Zone valve restores the operating mode"
status: Draft
priority: High
owner: R. Nabil
former-id: TC-AHQ3K8
parent: REQ-XGWSK2K
order: aL
links:
  - type: verifies
    target: REQ-R47232G
    confirmed: 29ca05a07a2d
  - type: verifies
    target: REQ-7BMF3KR
    confirmed: 19719b00925d
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Authenticate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
