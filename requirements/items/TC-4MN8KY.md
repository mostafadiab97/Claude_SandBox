---
id: TC-4MN8KY
type: test-case
title: "Verify: Enclosure calibrates relay events"
status: Review
priority: High
owner: R. Nabil
parent: INFO-MACGC3
order: 20
links:
  - type: verifies
    target: SYS-42GJXH
  - type: verifies
    target: SW-DCD4TG
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Log the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
