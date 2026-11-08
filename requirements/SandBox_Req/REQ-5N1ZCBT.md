---
id: REQ-5N1ZCBT
type: test-case
title: "Verify: Tamper detection reports humidity values"
status: Approved
priority: High
owner: S. Adel
former-id: TC-89FHKA
parent: REQ-K6FGAY0
order: b0R
links:
  - type: verifies
    target: REQ-GFFZN3Z
    confirmed: 3f8b6bcfec69
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Store access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
