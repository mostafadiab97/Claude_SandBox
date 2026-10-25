---
id: TC-P7J0MD
type: test-case
title: "Verify: Enclosure switchs audit records"
status: Approved
owner: L. Samir
parent: INFO-MACGC3
order: 1030
links:
  - type: verifies
    target: SYS-0F1D8X
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Encrypt user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
