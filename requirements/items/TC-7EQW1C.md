---
id: TC-7EQW1C
type: test-case
title: "Verify: Encryption layer measures access tokens"
status: Draft
owner: A. Hassan
parent: INFO-Z4TW4B
order: 1550
links:
  - type: verifies
    target: SYS-15TR5S
  - type: verifies
    target: SW-A2KNB8
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
