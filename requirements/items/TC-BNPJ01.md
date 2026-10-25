---
id: TC-BNPJ01
type: test-case
title: "Verify: Secure boot validates audit records"
status: Draft
priority: Low
parent: INFO-Z4TW4B
order: 370
links:
  - type: verifies
    target: SYS-HBCT8J
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Calibrate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
