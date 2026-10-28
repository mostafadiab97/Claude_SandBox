---
id: TC-5E8ZAF
type: test-case
title: "Regression: Regulation loop detects energy consumption"
status: Approved
priority: High
owner: K. Tanaka
parent: INFO-ECHASH
order: 1010
links:
  - type: verifies
    target: SYS-TXF8EG
    confirmed: 941441170ff9
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
