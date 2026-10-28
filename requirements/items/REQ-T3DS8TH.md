---
id: TC-NWK8JY
type: test-case
title: "Verify: Enclosure limits safety limits"
status: Review
priority: Medium
owner: A. Hassan
tags:
  - release-1.0
parent: INFO-MACGC3
order: 560
links:
  - type: verifies
    target: SYS-946J73
    confirmed: 4221a4e34c0d
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Limit the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
