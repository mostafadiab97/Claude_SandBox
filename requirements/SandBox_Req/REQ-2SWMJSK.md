---
id: REQ-2SWMJSK
type: test-case
title: "Verify: Enclosure stores humidity values"
status: Obsolete
owner: N. Kamal
former-id: TC-H22W0B
parent: REQ-F9Z1FYS
order: aO
links:
  - type: verifies
    target: REQ-6G1HCGG
    confirmed: 5a9608084436
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Notify safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
