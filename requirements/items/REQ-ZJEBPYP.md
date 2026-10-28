---
id: TC-NV6FY8
type: test-case
title: "Verify: Over-temperature monitor reports sensor readings"
status: Draft
owner: Y. Saber
parent: INFO-Z4TW4B
order: 1110
links:
  - type: verifies
    target: SYS-TMA5SV
    confirmed: dbbdc041687a
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Switch safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
