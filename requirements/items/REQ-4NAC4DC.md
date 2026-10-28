---
id: REQ-4NAC4DC
type: test-case
title: "Verify: Enclosure reports the room temperature"
status: Approved
priority: Medium
owner: N. Kamal
former-id: TC-7WJQNP
parent: REQ-F9Z1FYS
order: b11
links:
  - type: verifies
    target: REQ-N0KC5GA
    confirmed: d3225946a824
  - type: verifies
    target: REQ-HBMS0PS
    confirmed: 77cb9f1654aa
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Validate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
