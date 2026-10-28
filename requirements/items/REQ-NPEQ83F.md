---
id: REQ-NPEQ83F
type: test-case
title: "Verify: Main PCB measures user preferences"
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - power
former-id: TC-0HKJXN
parent: REQ-F9Z1FYS
order: aF
links:
  - type: verifies
    target: REQ-7DP8FH8
    confirmed: 65250d626484
  - type: verifies
    target: REQ-N3YPC85
    confirmed: ee73796f28b9
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Limit sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
