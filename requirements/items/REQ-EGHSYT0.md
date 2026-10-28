---
id: TC-JGS4PD
type: test-case
title: "Verify: Tamper detection reports relay events"
status: Approved
priority: Medium
owner: L. Samir
parent: INFO-Z4TW4B
order: 1360
links:
  - type: verifies
    target: SYS-7GMJTA
    confirmed: 3901ff02971d
  - type: verifies
    target: SW-52NFB3
    confirmed: 11bb078b09cd
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Authenticate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
