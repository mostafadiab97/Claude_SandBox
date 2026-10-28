---
id: REQ-QQMWGP1
type: test-case
title: "Verify: Over-temperature monitor restores audit records"
status: Draft
owner: É. Laurent
former-id: TC-KPETKT
parent: REQ-K6FGAY0
order: b13
links:
  - type: verifies
    target: REQ-5XTHHVF
    confirmed: 6f66a4941544
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Calibrate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
