---
id: REQ-M0VXYCQ
type: test-case
title: "Verify: Touch display measures sensor readings"
status: Draft
priority: Medium
owner: J. Müller
former-id: TC-Y829BD
parent: REQ-Y9VHHKA
order: b0V
links:
  - type: verifies
    target: REQ-C7D9Q3R
    confirmed: 06f883a1c81b
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Authenticate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
