---
id: TC-4FM2JJ
type: test-case
title: "Verify: Over-temperature monitor limits sensor readings"
status: Approved
owner: H. Mostafa
parent: INFO-Z4TW4B
order: 840
links:
  - type: verifies
    target: SYS-NVKX9K
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Measure audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
