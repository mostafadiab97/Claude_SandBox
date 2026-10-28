---
id: REQ-WT7C8SG
type: test-case
title: "Verify: Menu system measures humidity values"
status: Obsolete
priority: High
owner: H. Mostafa
former-id: TC-TYHZZ5
parent: REQ-Y9VHHKA
order: b0G
links:
  - type: verifies
    target: REQ-9GY82M1
    confirmed: d6a67816b8b6
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Detect humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
