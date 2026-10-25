---
id: TC-AN3CGF
type: test-case
title: "Verify: Pairing process measures firmware images"
status: Approved
priority: Medium
owner: É. Laurent
parent: INFO-F0M7VC
order: 230
links:
  - type: verifies
    target: SYS-JKNRQ3
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Store firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
