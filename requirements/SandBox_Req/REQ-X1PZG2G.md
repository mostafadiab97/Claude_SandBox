---
id: REQ-X1PZG2G
type: test-case
title: "Verify: Status LED switchs the set point"
status: Obsolete
priority: Medium
owner: محمد علي
former-id: TC-WKQC2D
parent: REQ-Y9VHHKA
order: aP
links:
  - type: verifies
    target: REQ-2965TER
    confirmed: 462438fa0d84
  - type: verifies
    target: REQ-T15RRBN
    confirmed: 3d295cfeb105
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Switch relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
