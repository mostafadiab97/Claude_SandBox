---
id: TC-RN8CXV
type: test-case
title: "Verify: Watchdog authenticates error conditions"
status: Review
owner: L. Samir
parent: INFO-Z4TW4B
order: 170
links:
  - type: verifies
    target: SYS-8MMGZP
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Display audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
