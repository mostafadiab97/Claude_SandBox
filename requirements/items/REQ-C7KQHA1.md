---
id: TC-JKM0AJ
type: test-case
title: "Verify: Secure boot measures schedule entries"
status: Draft
priority: High
parent: INFO-Z4TW4B
order: 690
links:
  - type: verifies
    target: SYS-EJR3YH
    confirmed: 7b3dac33b561
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Restore safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
