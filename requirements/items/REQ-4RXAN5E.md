---
id: REQ-4RXAN5E
type: test-case
title: "Verify: Menu system synchronises access tokens"
status: Approved
priority: High
owner: K. Tanaka
former-id: TC-GENX0F
parent: REQ-Y9VHHKA
order: b0W
links:
  - type: verifies
    target: REQ-F26X3E7
    confirmed: b91cd2a500bd
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Authenticate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
