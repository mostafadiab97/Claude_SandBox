---
id: TC-AA7JGK
type: test-case
title: "Verify: Encryption layer displays sensor readings"
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - regulatory
parent: INFO-Z4TW4B
order: 1490
links:
  - type: verifies
    target: SYS-NW2H4K
    confirmed: 061c07f59466
  - type: verifies
    target: SW-4YMQ7F
    confirmed: 9a7c3b69032e
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
