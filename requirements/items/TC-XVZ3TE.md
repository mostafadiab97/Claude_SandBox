---
id: TC-XVZ3TE
type: test-case
title: "Verify: Enclosure calibrates firmware images"
status: Draft
priority: Low
owner: É. Laurent
parent: INFO-MACGC3
order: 140
links:
  - type: verifies
    target: SYS-TTC476
  - type: verifies
    target: SW-XR8SYF
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Switch sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
