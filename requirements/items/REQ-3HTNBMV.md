---
id: TC-MPWW3C
type: test-case
title: "Verify: Power supply authenticates access tokens"
status: Approved
owner: K. Tanaka
parent: INFO-MACGC3
order: 230
links:
  - type: verifies
    target: SYS-4BMNYZ
    confirmed: 46035baf3f33
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Measure relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
