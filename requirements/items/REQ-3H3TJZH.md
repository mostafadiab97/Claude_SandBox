---
id: TC-7GNT21
type: test-case
title: "Regression: Zigbee radio authenticates sensor readings"
status: Review
priority: High
owner: L. Samir
parent: INFO-ECHASH
order: 1470
links:
  - type: verifies
    target: SYS-BCDQHB
    confirmed: ed0bba187a94
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
