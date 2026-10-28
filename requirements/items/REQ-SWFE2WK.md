---
id: TC-J48MS4
type: test-case
title: "Verify: Secure boot synchronises the connection state"
status: Review
priority: Medium
owner: J. Müller
parent: INFO-Z4TW4B
order: 710
links:
  - type: verifies
    target: SYS-FDJDP9
    confirmed: 3facea10cce7
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Calibrate the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
