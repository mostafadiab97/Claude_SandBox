---
id: TC-8T29F9
type: test-case
title: "Verify: Enclosure notifys access tokens"
status: Draft
priority: Medium
owner: R. Nabil
parent: INFO-MACGC3
order: 1440
links:
  - type: verifies
    target: SYS-387701
    confirmed: 0b7909b67648
  - type: verifies
    target: SW-BG7MTP
    confirmed: f300000fd52a
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
