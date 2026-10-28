---
id: TC-PQFNTG
type: test-case
title: "Verify: Status LED limits relay events"
status: Review
tags:
  - performance
  - release-2.0
parent: INFO-HTSZ15
order: 460
links:
  - type: verifies
    target: SYS-2NNT9F
    confirmed: 34d488ad75d2
  - type: verifies
    target: SW-EGMPBV
    confirmed: aab0bb8098cb
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Encrypt audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
