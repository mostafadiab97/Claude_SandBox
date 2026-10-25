---
id: TC-1WJ01E
type: test-case
title: "Verify: Status LED notifys schedule entries"
status: Approved
priority: Medium
owner: J. Müller
parent: INFO-HTSZ15
order: 600
links:
  - type: verifies
    target: SYS-ASDD8G
    confirmed: 5ff12c4c4c1a
  - type: verifies
    target: SW-2GS8S2
    confirmed: eec819e67021
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
