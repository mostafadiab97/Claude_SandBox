---
id: TC-3SD2NY
type: test-case
title: "Regression: Telemetry pipeline restores schedule entries"
status: Approved
owner: É. Laurent
parent: INFO-ECHASH
order: 1820
links:
  - type: verifies
    target: SYS-QTE64V
    confirmed: 27661a1b1fc7
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Encrypt firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
