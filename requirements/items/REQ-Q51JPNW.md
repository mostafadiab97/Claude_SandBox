---
id: TC-C0C8EJ
type: test-case
title: "Verify: Status LED displays the room temperature"
status: Approved
priority: High
owner: R. Nabil
tags:
  - cost
  - release-1.0
parent: INFO-HTSZ15
order: 1000
links:
  - type: verifies
    target: SYS-36NNDJ
    confirmed: 100c60ddc325
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Measure audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
