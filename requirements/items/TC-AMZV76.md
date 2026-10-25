---
id: TC-AMZV76
type: test-case
title: "Verify: Tamper detection detects error conditions"
status: Approved
owner: Y. Saber
parent: INFO-Z4TW4B
order: 830
links:
  - type: verifies
    target: SYS-HAHB1Q
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Encrypt audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
