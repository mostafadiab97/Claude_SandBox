---
id: TC-DS9K5M
type: test-case
title: "Verify: Cloud backend notifys safety limits"
status: Approved
priority: Medium
owner: L. Samir
parent: INFO-7P4D8D
order: 790
links:
  - type: verifies
    target: SYS-AH9G64
    confirmed: e3199b24d9a9
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Log the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
