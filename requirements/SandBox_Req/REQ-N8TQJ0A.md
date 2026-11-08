---
id: REQ-N8TQJ0A
type: test-case
title: "Verify: Tamper detection encrypts relay events"
status: Draft
priority: Low
tags:
  - security
former-id: TC-ANN5KE
parent: REQ-K6FGAY0
order: aU
links:
  - type: verifies
    target: REQ-D4ZA4NM
    confirmed: 1331a264167a
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Detect energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
