---
id: REQ-VBX4Z63
type: test-case
title: "Verify: Over-temperature monitor restores sensor readings"
status: Review
priority: Low
owner: L. Samir
tags:
  - power
former-id: TC-PBTRWG
parent: REQ-K6FGAY0
order: aL
links:
  - type: verifies
    target: REQ-M89P0JQ
    confirmed: 2f261bacbfde
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
