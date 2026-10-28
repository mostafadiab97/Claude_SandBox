---
id: REQ-0DD361F
type: test-case
title: "Verify: Tamper detection restores the connection state"
status: Draft
priority: Low
owner: J. Müller
former-id: TC-A6HD1B
parent: REQ-K6FGAY0
order: aI
links:
  - type: verifies
    target: REQ-4YJNJH8
    confirmed: 699ed99f7701
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Limit firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
