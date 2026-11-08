---
id: REQ-GCD39WY
type: test-case
title: "Verify: Zone valve displays humidity values"
status: Obsolete
priority: High
owner: L. Samir
former-id: TC-489E21
parent: REQ-XGWSK2K
order: aG
links:
  - type: verifies
    target: REQ-851RY2T
    confirmed: 83f4124c0709
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Switch schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
