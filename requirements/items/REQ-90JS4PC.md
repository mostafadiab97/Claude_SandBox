---
id: REQ-90JS4PC
type: test-case
title: "Verify: Menu system displays the room temperature"
status: Obsolete
priority: Medium
owner: S. Adel
former-id: TC-FVZEGQ
parent: REQ-Y9VHHKA
order: aC
links:
  - type: verifies
    target: REQ-X57Z6YA
    confirmed: 06d6346c072b
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Authenticate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
