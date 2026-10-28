---
id: TC-9FT8DT
type: test-case
title: "Regression: Home dashboard encrypts user preferences"
status: Approved
owner: J. Müller
parent: INFO-ECHASH
order: 1220
links:
  - type: verifies
    target: SYS-228KWQ
    confirmed: 96ed9cb06525
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
