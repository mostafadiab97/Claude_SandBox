---
id: TC-2M4SX3
type: test-case
title: "Verify: Tamper detection validates user preferences"
status: Draft
priority: High
owner: R. Nabil
parent: INFO-Z4TW4B
order: 880
links:
  - type: verifies
    target: SYS-BGEM84
    confirmed: 7c077fec9862
  - type: verifies
    target: SW-JE2GH1
    confirmed: 00c6a3ef7be5
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Switch the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
