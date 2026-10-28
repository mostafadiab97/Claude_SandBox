---
id: REQ-28KHFPX
type: test-case
title: "Verify: Zigbee radio restores relay events"
status: Review
owner: N. Kamal
former-id: TC-CKFX85
parent: REQ-67RQXCK
order: a5
links:
  - type: verifies
    target: REQ-8782FZK
    confirmed: cfcb93c868dc
  - type: verifies
    target: REQ-G5DMK9M
    confirmed: 230daeb78b52
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Authenticate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
