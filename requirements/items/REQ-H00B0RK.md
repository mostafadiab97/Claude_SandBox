---
id: TC-571QHG
type: test-case
title: "Verify: Status LED displays sensor readings"
status: Draft
priority: Medium
owner: L. Samir
parent: INFO-HTSZ15
order: 240
links:
  - type: verifies
    target: SYS-AHMEKC
    confirmed: 5aa806091a04
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Switch the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
