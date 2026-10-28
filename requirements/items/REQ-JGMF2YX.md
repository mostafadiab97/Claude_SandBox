---
id: REQ-JGMF2YX
type: test-case
title: "Verify: Status LED authenticates sensor readings"
status: Approved
priority: High
owner: A. Hassan
tags:
  - regulatory
  - accessibility
former-id: TC-E0MD39
parent: REQ-Y9VHHKA
order: b0X
links:
  - type: verifies
    target: REQ-GF42JSW
    confirmed: cd0fa22d1fa7
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Store schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
