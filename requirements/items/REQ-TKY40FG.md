---
id: TC-YW2W19
type: test-case
title: "Verify: Encryption layer logs user preferences"
status: Draft
priority: High
owner: S. Adel
parent: INFO-Z4TW4B
order: 1380
links:
  - type: verifies
    target: SYS-SNV0V5
    confirmed: e469f30b51d1
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Detect relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
