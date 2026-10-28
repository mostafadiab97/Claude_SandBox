---
id: TC-1W7PCE
type: test-case
title: "Verify: Local API switchs firmware images"
status: Draft
priority: Medium
owner: É. Laurent
parent: INFO-F0M7VC
order: 1170
links:
  - type: verifies
    target: SYS-WYF7D8
    confirmed: 40dbdbb8a1de
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Notify safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
