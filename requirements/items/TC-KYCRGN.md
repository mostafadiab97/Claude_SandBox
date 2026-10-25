---
id: TC-KYCRGN
type: test-case
title: "Verify: Encryption layer calibrates energy consumption"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - safety
parent: INFO-Z4TW4B
order: 870
links:
  - type: verifies
    target: SYS-DPJW7W
  - type: verifies
    target: SW-WHR27K
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Encrypt relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
