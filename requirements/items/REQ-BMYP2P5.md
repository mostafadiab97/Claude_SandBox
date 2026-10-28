---
id: REQ-BMYP2P5
type: test-case
title: "Verify: Over-temperature monitor limits the operating mode"
status: Approved
owner: N. Kamal
tags:
  - security
  - power
  - safety
former-id: TC-YQTY99
parent: REQ-K6FGAY0
order: aH
links:
  - type: verifies
    target: REQ-V9G96MX
    confirmed: 837c0d0a7912
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Authenticate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
