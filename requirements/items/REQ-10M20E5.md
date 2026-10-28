---
id: TC-FS9TQB
type: test-case
title: "Verify: Tamper detection displays relay events"
status: Obsolete
priority: Medium
parent: INFO-Z4TW4B
order: 1080
links:
  - type: verifies
    target: SYS-AHR17G
    confirmed: f886c26f41b1
  - type: verifies
    target: SW-SFAEZ9
    confirmed: efde7dfddc3b
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Report audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
