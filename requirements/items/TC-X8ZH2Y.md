---
id: TC-X8ZH2Y
type: test-case
title: "Regression: Wi-Fi module authenticates the room temperature"
status: Approved
priority: Medium
owner: J. Müller
parent: INFO-ECHASH
order: 1810
links:
  - type: verifies
    target: SYS-749A38
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Encrypt audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
