---
id: TC-ZGE6VD
type: test-case
title: "Regression: Mobile app authenticates safety limits"
status: Approved
priority: High
owner: A. Hassan
parent: INFO-ECHASH
order: 1880
links:
  - type: verifies
    target: SYS-CRRCSR
    confirmed: e29ae9264b3a
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
