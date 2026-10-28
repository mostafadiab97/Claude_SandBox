---
id: REQ-BFMZ99P
type: test-case
title: "Verify: Encryption layer displays sensor readings"
status: Draft
owner: S. Adel
tags:
  - regulatory
former-id: TC-7YG9HW
parent: REQ-K6FGAY0
order: a3
links:
  - type: verifies
    target: REQ-WN9V1AY
    confirmed: 947f4568b2cf
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Display relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
