---
id: REQ-V2WV6PY
type: test-case
title: "Verify: Over-temperature monitor limits the set point"
status: Approved
owner: L. Samir
tags:
  - EMC
former-id: TC-1YM1D3
parent: REQ-K6FGAY0
order: b1C
links:
  - type: verifies
    target: REQ-9JQBZHM
    confirmed: 3b09685c237a
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Report relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
