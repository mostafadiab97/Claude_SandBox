---
id: TC-N8DA8A
type: test-case
title: "Verify: Encryption layer limits humidity values"
status: Review
priority: Medium
owner: L. Samir
parent: INFO-Z4TW4B
order: 20
links:
  - type: verifies
    target: SYS-BHD8S6
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Display the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
