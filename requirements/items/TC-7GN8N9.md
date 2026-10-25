---
id: TC-7GN8N9
type: test-case
title: "Verify: Local API reports user preferences"
status: Approved
priority: Medium
owner: A. Hassan
parent: INFO-F0M7VC
order: 90
links:
  - type: verifies
    target: SYS-66QHTN
    confirmed: 65154f9b889c
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Measure sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
