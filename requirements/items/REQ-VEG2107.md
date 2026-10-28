---
id: REQ-VEG2107
type: test-case
title: "Verify: Touch display logs the connection state"
status: Draft
owner: N. Kamal
former-id: TC-NAS8NX
parent: REQ-Y9VHHKA
order: b11
links:
  - type: verifies
    target: REQ-ZD3BDSG
    confirmed: 844d91cb4e42
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
