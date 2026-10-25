---
id: TC-YCXDCH
type: test-case
title: "Verify: Enclosure displays the operating mode"
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - performance
  - customer-request
  - power
parent: INFO-MACGC3
order: 390
links:
  - type: verifies
    target: SYS-FVC51X
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
