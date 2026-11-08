---
id: REQ-JAYG6Y6
type: test-case
title: "Verify: Menu system measures schedule entries"
status: Draft
priority: Low
owner: R. Nabil
former-id: TC-WD0169
parent: REQ-Y9VHHKA
order: aD
links:
  - type: verifies
    target: REQ-JCMN4T1
    confirmed: a7bb3114a08e
  - type: verifies
    target: REQ-8R81M1Y
    confirmed: 254e4c6d5905
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Display schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
