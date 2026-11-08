---
id: REQ-MNM0J82
type: test-case
title: "Verify: Home dashboard encrypts firmware images"
status: Obsolete
priority: High
owner: محمد علي
former-id: TC-6SJD3D
parent: REQ-WR5ZJN9
order: aQ
links:
  - type: verifies
    target: REQ-F11HQ72
    confirmed: 832b55acc75f
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Validate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
