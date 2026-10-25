---
id: TC-XYXDAE
type: test-case
title: "Verify: Mobile app measures access tokens"
status: Draft
owner: N. Kamal
parent: INFO-J0FETE
order: 1340
links:
  - type: verifies
    target: SYS-M63JNN
  - type: verifies
    target: SW-V0S8WJ
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Log safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
