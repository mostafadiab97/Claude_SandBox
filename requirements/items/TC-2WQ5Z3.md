---
id: TC-2WQ5Z3
type: test-case
title: "Verify: Pairing process calibrates firmware images"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - release-1.0
  - performance
parent: INFO-F0M7VC
order: 770
links:
  - type: verifies
    target: SYS-HY185S
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
