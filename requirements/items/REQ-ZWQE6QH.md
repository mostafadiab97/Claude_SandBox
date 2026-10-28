---
id: REQ-ZWQE6QH
type: test-case
title: "Verify: Bluetooth LE link reports sensor readings"
status: Review
priority: Medium
owner: محمد علي
former-id: TC-GJBCND
parent: REQ-67RQXCK
order: av
links:
  - type: verifies
    target: REQ-84ZV56S
    confirmed: ff918beefe64
  - type: verifies
    target: REQ-FF6HYWX
    confirmed: c4b55551f995
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Store firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
