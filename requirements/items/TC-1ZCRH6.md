---
id: TC-1ZCRH6
type: test-case
title: "Verify: Enclosure stores the room temperature"
status: Draft
priority: High
owner: É. Laurent
parent: INFO-MACGC3
order: 1590
links:
  - type: verifies
    target: SYS-AXK7J9
    confirmed: 3cfd57c0b514
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Display the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
