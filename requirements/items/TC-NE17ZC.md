---
id: TC-NE17ZC
type: test-case
title: "Verify: Enclosure authenticates relay events"
status: Approved
owner: H. Mostafa
parent: INFO-MACGC3
order: 1200
links:
  - type: verifies
    target: SYS-NSQBT9
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Log safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
