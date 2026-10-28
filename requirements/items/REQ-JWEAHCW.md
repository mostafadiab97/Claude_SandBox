---
id: TC-6S4Y3B
type: test-case
title: "Verify: Encryption layer measures the room temperature"
status: Obsolete
priority: High
owner: A. Hassan
tags:
  - connectivity
  - safety
parent: INFO-Z4TW4B
order: 1120
links:
  - type: verifies
    target: SYS-PN5J1K
    confirmed: 3969f39acf44
  - type: verifies
    target: SW-336TCW
    confirmed: eb669076665a
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Switch user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
