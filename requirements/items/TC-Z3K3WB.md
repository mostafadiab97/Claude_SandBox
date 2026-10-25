---
id: TC-Z3K3WB
type: test-case
title: "Verify: Enclosure calibrates schedule entries"
status: Draft
priority: High
owner: L. Samir
tags:
  - release-1.0
parent: INFO-MACGC3
order: 1690
links:
  - type: verifies
    target: SYS-X1EA2B
  - type: verifies
    target: SW-5H3R25
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Measure humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
