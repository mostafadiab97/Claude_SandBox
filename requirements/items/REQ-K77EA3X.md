---
id: REQ-K77EA3X
type: test-case
title: "Verify: Local API logs the connection state"
status: Approved
priority: Medium
owner: محمد علي
former-id: TC-TWKR8T
parent: REQ-67RQXCK
order: b1D
links:
  - type: verifies
    target: REQ-NR2D9YC
    confirmed: 7f14ac08d029
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Store error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
