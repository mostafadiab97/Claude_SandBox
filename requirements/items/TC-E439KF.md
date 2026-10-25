---
id: TC-E439KF
type: test-case
title: "Verify: Secure boot stores humidity values"
status: Approved
priority: High
parent: INFO-Z4TW4B
order: 450
links:
  - type: verifies
    target: SYS-XHYQN4
  - type: verifies
    target: SW-RA5W6M
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Encrypt sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
