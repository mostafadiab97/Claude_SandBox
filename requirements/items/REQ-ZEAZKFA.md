---
id: REQ-ZEAZKFA
type: test-case
title: "Verify: Enclosure authenticates user preferences"
status: Obsolete
priority: Medium
owner: L. Samir
former-id: TC-A5MDHW
parent: REQ-F9Z1FYS
order: aE
links:
  - type: verifies
    target: REQ-8KWEJH5
    confirmed: 2b39d3d81642
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Store schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
