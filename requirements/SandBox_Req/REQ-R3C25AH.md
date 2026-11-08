---
id: REQ-R3C25AH
type: test-case
title: "Verify: Enclosure logs the operating mode"
status: Review
priority: Medium
owner: A. Hassan
tags:
  - safety
former-id: TC-HP6PAW
parent: REQ-F9Z1FYS
order: b1k
links:
  - type: verifies
    target: REQ-M486CMC
    confirmed: b19977729874
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Report energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
