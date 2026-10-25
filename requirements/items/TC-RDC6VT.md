---
id: TC-RDC6VT
type: test-case
title: "Verify: Relay board stores audit records"
status: Approved
priority: Medium
owner: S. Adel
parent: INFO-MACGC3
order: 170
links:
  - type: verifies
    target: SYS-422XBG
    confirmed: 5a6b1faa9b43
  - type: verifies
    target: SW-QQWQ93
    confirmed: 901c1d122bd5
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Encrypt schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
