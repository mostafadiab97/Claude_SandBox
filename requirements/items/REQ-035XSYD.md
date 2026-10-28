---
id: TC-12FCER
type: test-case
title: "Regression: Backlight synchronises firmware images"
status: Approved
priority: Medium
owner: A. Hassan
parent: INFO-ECHASH
order: 1570
links:
  - type: verifies
    target: SYS-JWK81Y
    confirmed: 8656508483c4
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
