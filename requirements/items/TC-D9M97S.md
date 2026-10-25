---
id: TC-D9M97S
type: test-case
title: "Verify: Cloud backend restores sensor readings"
status: Approved
priority: High
owner: Y. Saber
parent: INFO-7P4D8D
order: 1430
links:
  - type: verifies
    target: SYS-JGSYAF
  - type: verifies
    target: SW-ZS27TP
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Display user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
