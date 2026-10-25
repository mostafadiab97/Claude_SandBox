---
id: TC-FZQT97
type: test-case
title: "Verify: Menu system encrypts sensor readings"
status: Approved
priority: Low
owner: K. Tanaka
parent: INFO-HTSZ15
order: 190
links:
  - type: verifies
    target: SYS-9YAX2Y
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Display relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
