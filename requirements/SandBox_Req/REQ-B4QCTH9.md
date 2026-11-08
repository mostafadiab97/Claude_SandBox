---
id: REQ-B4QCTH9
type: test-case
title: "Verify: Menu system notifys the set point"
status: Review
priority: Medium
owner: L. Samir
tags:
  - i18n
  - accessibility
  - safety
former-id: TC-WXD3Q2
parent: REQ-Y9VHHKA
order: b1G
links:
  - type: verifies
    target: REQ-SF9Q7GE
    confirmed: 8bf9018cb7b2
  - type: verifies
    target: REQ-K3MWQ69
    confirmed: 588f622701dc
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Log safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
