---
id: TC-REYFKF
type: test-case
title: "Verify: Relay board encrypts access tokens"
status: Obsolete
priority: Medium
owner: K. Tanaka
parent: INFO-MACGC3
order: 570
links:
  - type: verifies
    target: SYS-47FSG3
    confirmed: 50f3571b1236
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Limit user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
