---
id: TC-9YCE6S
type: test-case
title: "Regression: Login screen stores the connection state"
status: Approved
owner: K. Tanaka
parent: INFO-ECHASH
order: 800
links:
  - type: verifies
    target: SYS-8P54CP
    confirmed: 83be93bab647
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
