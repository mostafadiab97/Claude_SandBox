---
id: TC-BTTBVQ
type: test-case
title: "Verify: Enclosure logs the connection state"
status: Draft
owner: A. Hassan
parent: INFO-MACGC3
order: 1560
links:
  - type: verifies
    target: SYS-XRP95E
  - type: verifies
    target: SW-H767RS
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Detect the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
