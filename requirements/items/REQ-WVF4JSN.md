---
id: REQ-WVF4JSN
type: test-case
title: "Verify: Menu system restores humidity values"
status: Obsolete
priority: High
tags:
  - release-2.0
  - regulatory
former-id: TC-W9BEPF
parent: REQ-Y9VHHKA
order: b0C
links:
  - type: verifies
    target: REQ-JVYQ4PD
    confirmed: 453482be94f2
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Restore firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
