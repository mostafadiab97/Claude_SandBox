---
id: REQ-WATAQN4
type: test-case
title: "Verify: Mobile app limits relay events"
status: Review
former-id: TC-3ED6VX
parent: REQ-WR5ZJN9
order: b0G
links:
  - type: verifies
    target: REQ-6VREK7W
    confirmed: 5e8b057ab780
  - type: verifies
    target: REQ-C19ECNK
    confirmed: 4ca724906785
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Detect the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
