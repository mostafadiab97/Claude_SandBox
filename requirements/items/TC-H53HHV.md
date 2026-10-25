---
id: TC-H53HHV
type: test-case
title: "Verify: Pairing process logs the operating mode"
status: Review
priority: Medium
owner: A. Hassan
tags:
  - regulatory
  - security
parent: INFO-F0M7VC
order: 1390
links:
  - type: verifies
    target: SYS-MQPMA3
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Report firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
