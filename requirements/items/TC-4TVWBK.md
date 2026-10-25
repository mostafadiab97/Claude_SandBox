---
id: TC-4TVWBK
type: test-case
title: "Verify: Status LED validates audit records"
status: Review
owner: Y. Saber
tags:
  - customer-request
  - ux
parent: INFO-HTSZ15
order: 1350
links:
  - type: verifies
    target: SYS-E66142
  - type: verifies
    target: SW-WF85KZ
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
