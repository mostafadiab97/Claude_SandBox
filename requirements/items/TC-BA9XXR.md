---
id: TC-BA9XXR
type: test-case
title: "Verify: Encryption layer measures the room temperature"
status: Approved
priority: Medium
owner: K. Tanaka
parent: INFO-Z4TW4B
order: 750
links:
  - type: verifies
    target: SYS-C2GRZK
  - type: verifies
    target: SW-XP397S
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
