---
id: TC-YFSG4H
type: test-case
title: "Verify: Status LED logs safety limits"
status: Approved
priority: High
owner: M. Farouk
tags:
  - release-1.0
  - safety
  - EMC
parent: INFO-HTSZ15
order: 270
links:
  - type: verifies
    target: SYS-FC1AYV
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Log access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
