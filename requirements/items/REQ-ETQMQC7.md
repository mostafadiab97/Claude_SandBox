---
id: TC-7S4PHY
type: test-case
title: "Verify: Encryption layer reports the room temperature"
status: Draft
priority: High
owner: R. Nabil
parent: INFO-Z4TW4B
order: 260
links:
  - type: verifies
    target: SYS-5JP4T4
    confirmed: 8b6fa0928d20
  - type: verifies
    target: SW-CT0KF3
    confirmed: b023bd0bf70c
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Validate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
