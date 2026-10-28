---
id: TC-X7ESSA
type: test-case
title: "Verify: Pairing process limits energy consumption"
status: Review
priority: Medium
owner: R. Nabil
parent: INFO-F0M7VC
order: 500
links:
  - type: verifies
    target: SYS-KJZDA6
    confirmed: cceccc292cf6
  - type: verifies
    target: SW-V7TB34
    confirmed: bf196a7be830
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Notify access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
