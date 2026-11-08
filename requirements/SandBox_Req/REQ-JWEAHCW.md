---
id: REQ-JWEAHCW
type: test-case
title: "Verify: Encryption layer measures the room temperature"
status: Obsolete
priority: High
owner: A. Hassan
tags:
  - connectivity
  - safety
former-id: TC-6S4Y3B
parent: REQ-K6FGAY0
order: b0n
links:
  - type: verifies
    target: REQ-C0Z47PJ
    confirmed: 3969f39acf44
  - type: verifies
    target: REQ-XMSVC1K
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
