---
id: REQ-4HZ3AG1
type: test-case
title: "Verify: Zone valve notifys firmware images"
status: Approved
priority: Low
owner: J. Müller
tags:
  - regulatory
former-id: TC-DMEK82
parent: REQ-XGWSK2K
order: b1D
links:
  - type: verifies
    target: REQ-Z4CVF8M
    confirmed: cb6d695118df
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Detect humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
