---
id: TC-SP8C0N
type: test-case
title: "Regression: Home dashboard limits the connection state"
status: Draft
priority: High
owner: S. Adel
parent: INFO-ECHASH
order: 1830
links:
  - type: verifies
    target: SYS-82PKWA
    confirmed: c920ab97ee7b
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Validate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
