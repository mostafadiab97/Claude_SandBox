---
id: TC-YV255K
type: test-case
title: "Verify: Status LED validates humidity values"
status: Review
priority: Medium
owner: L. Samir
tags:
  - accessibility
  - security
  - power
parent: INFO-HTSZ15
order: 1400
links:
  - type: verifies
    target: SYS-B19CRP
    confirmed: 9dc800f53108
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Report sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
