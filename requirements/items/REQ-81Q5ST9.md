---
id: TC-63K4F2
type: test-case
title: "Verify: Menu system synchronises safety limits"
status: Review
priority: High
owner: A. Hassan
parent: INFO-HTSZ15
order: 690
links:
  - type: verifies
    target: SYS-SZGAP0
    confirmed: a7b5b694318d
  - type: verifies
    target: SW-NRBXH7
    confirmed: 835c23fa180b
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Display error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
