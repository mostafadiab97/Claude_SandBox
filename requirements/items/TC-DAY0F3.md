---
id: TC-DAY0F3
type: test-case
title: "Verify: Encryption layer authenticates the operating mode"
status: Review
priority: Medium
owner: H. Mostafa
parent: INFO-Z4TW4B
order: 1500
links:
  - type: verifies
    target: SYS-3JQGM8
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Log schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
