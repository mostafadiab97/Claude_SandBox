---
id: TC-ZWEGMJ
type: test-case
title: "Verify: Encryption layer authenticates humidity values"
status: Draft
priority: Medium
owner: محمد علي
parent: INFO-Z4TW4B
order: 420
links:
  - type: verifies
    target: SYS-5D666J
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Detect sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
