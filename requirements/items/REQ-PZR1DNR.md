---
id: TC-6JGA6A
type: test-case
title: "Verify: Mobile app authenticates relay events"
status: Draft
priority: Low
owner: S. Adel
parent: INFO-J0FETE
order: 640
links:
  - type: verifies
    target: SYS-263BJQ
    confirmed: 545c48596828
  - type: verifies
    target: SW-6PQ479
    confirmed: 14014a8e9ebe
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Detect the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
