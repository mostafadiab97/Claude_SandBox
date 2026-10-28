---
id: TC-0277BP
type: test-case
title: "Verify: Secure boot switchs the set point"
status: Approved
priority: Medium
owner: M. Farouk
parent: INFO-Z4TW4B
order: 340
links:
  - type: verifies
    target: SYS-9FTG47
    confirmed: 6b7150a5bc62
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Display relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
