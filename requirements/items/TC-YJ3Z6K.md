---
id: TC-YJ3Z6K
type: test-case
title: "Verify: Main PCB authenticates error conditions"
status: Obsolete
parent: INFO-MACGC3
order: 30
links:
  - type: verifies
    target: SYS-J73TGA
  - type: verifies
    target: SW-YV9696
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Report access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
