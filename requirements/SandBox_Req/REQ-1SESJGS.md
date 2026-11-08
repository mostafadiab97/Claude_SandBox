---
id: REQ-1SESJGS
type: test-case
title: "Verify: Menu system authenticates access tokens"
status: Obsolete
priority: Medium
owner: H. Mostafa
former-id: TC-0PK9AY
parent: REQ-Y9VHHKA
order: b0Y
links:
  - type: verifies
    target: REQ-2E3JP7D
    confirmed: 604e69a0125a
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Calibrate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
