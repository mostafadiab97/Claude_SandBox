---
id: TC-BZ13NF
type: test-case
title: "Verify: Local API reports audit records"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - connectivity
  - ux
parent: INFO-F0M7VC
order: 420
links:
  - type: verifies
    target: SYS-B99DV1
    confirmed: 4cbe1396d101
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Report humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
