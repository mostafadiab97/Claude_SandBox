---
id: REQ-RFSBEPC
type: test-case
title: "Verify: Menu system stores the room temperature"
status: Obsolete
priority: Medium
owner: K. Tanaka
tags:
  - i18n
former-id: TC-N35PY4
parent: REQ-Y9VHHKA
order: b1P
links:
  - type: verifies
    target: REQ-KDBFG7Y
    confirmed: 6324bbe48da8
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Store audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
