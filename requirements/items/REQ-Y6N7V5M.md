---
id: REQ-Y6N7V5M
type: test-case
title: "Verify: Power supply reports relay events"
status: Draft
priority: High
owner: S. Adel
former-id: TC-6284FY
parent: REQ-F9Z1FYS
order: b0D
links:
  - type: verifies
    target: REQ-TJYAHYG
    confirmed: 78f3618e6442
  - type: verifies
    target: REQ-7BMF3KR
    confirmed: 19719b00925d
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
