---
id: TC-V1EAJ5
type: test-case
title: "Verify: Power supply detects safety limits"
status: Approved
priority: Low
parent: INFO-MACGC3
order: 1360
links:
  - type: verifies
    target: SYS-JJBC0A
    confirmed: 33302d5c9847
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Authenticate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
