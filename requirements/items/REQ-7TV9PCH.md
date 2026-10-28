---
id: REQ-7TV9PCH
type: test-case
title: "Verify: Tamper detection notifys audit records"
status: Obsolete
priority: Medium
owner: M. Farouk
former-id: TC-Z71QV0
parent: REQ-K6FGAY0
order: b02
links:
  - type: verifies
    target: REQ-GT97WSE
    confirmed: 64cf1ce65b09
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
