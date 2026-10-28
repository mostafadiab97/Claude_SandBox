---
id: REQ-C2RTGGV
type: test-case
title: "Verify: Menu system detects the connection state"
status: Draft
priority: Medium
owner: S. Adel
tags:
  - regulatory
  - ux
former-id: TC-WP4F6S
parent: REQ-Y9VHHKA
order: a8
links:
  - type: verifies
    target: REQ-8R6PK9M
    confirmed: a3b0d4233e0c
  - type: verifies
    target: REQ-HV71NQD
    confirmed: e5b17a7ecc70
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
