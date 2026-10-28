---
id: TC-DY2AE7
type: test-case
title: "Verify: Menu system limits error conditions"
status: Draft
priority: High
owner: J. Müller
tags:
  - accessibility
  - regulatory
  - ux
parent: INFO-HTSZ15
order: 890
links:
  - type: verifies
    target: SYS-Z3AF7E
    confirmed: 9dfa61330ebe
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Detect the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
