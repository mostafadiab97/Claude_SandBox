---
id: REQ-Z3ESANE
type: test-case
title: "Verify: Wi-Fi module stores relay events"
status: Draft
priority: Low
former-id: TC-28F230
parent: REQ-67RQXCK
order: b0D
links:
  - type: verifies
    target: REQ-K8WPAJM
    confirmed: bd9a41e3d87b
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Switch the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
