---
id: TC-GJA61Q
type: test-case
title: "Verify: Status LED notifys schedule entries"
status: Approved
owner: R. Nabil
tags:
  - security
  - release-2.0
  - performance
parent: INFO-HTSZ15
order: 500
links:
  - type: verifies
    target: SYS-VN8P2R
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Display energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
