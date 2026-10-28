---
id: TC-P198C0
type: test-case
title: "Verify: Encryption layer stores safety limits"
status: Obsolete
priority: Medium
tags:
  - cost
  - accessibility
  - i18n
parent: INFO-Z4TW4B
order: 10
links:
  - type: verifies
    target: SYS-RW42CM
    confirmed: 28c35d155880
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Log schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
