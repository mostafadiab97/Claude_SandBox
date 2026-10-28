---
id: TC-95M7JW
type: test-case
title: "Verify: Watchdog detects firmware images"
status: Approved
priority: High
owner: R. Nabil
parent: INFO-Z4TW4B
order: 850
links:
  - type: verifies
    target: SYS-JN1V9K
    confirmed: 648ea81ae922
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Display relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
