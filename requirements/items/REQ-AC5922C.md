---
id: TC-XNGE8D
type: test-case
title: "Regression: Schedule editor detects energy consumption"
status: Obsolete
priority: High
owner: L. Samir
parent: INFO-ECHASH
order: 1550
links:
  - type: verifies
    target: SYS-3JPXMD
    confirmed: 429b4766228a
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
