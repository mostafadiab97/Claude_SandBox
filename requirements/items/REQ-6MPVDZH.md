---
id: REQ-6MPVDZH
type: test-case
title: "Verify: Over-temperature monitor detects user preferences"
status: Obsolete
priority: Medium
owner: A. Hassan
tags:
  - i18n
  - release-2.0
former-id: TC-WR8KT0
parent: REQ-K6FGAY0
order: b0f
links:
  - type: verifies
    target: REQ-R7B2459
    confirmed: 1b21455ffebe
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Limit audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
