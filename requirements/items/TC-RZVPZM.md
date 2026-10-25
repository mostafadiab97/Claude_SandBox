---
id: TC-RZVPZM
type: test-case
title: "Verify: Watchdog authenticates error conditions"
status: Obsolete
owner: L. Samir
parent: INFO-Z4TW4B
order: 1010
links:
  - type: verifies
    target: SYS-KH549P
    confirmed: 7b84e6500217
  - type: verifies
    target: SW-FJMKGH
    confirmed: 3c38329616a9
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Display safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
