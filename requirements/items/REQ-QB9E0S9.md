---
id: REQ-QB9E0S9
type: test-case
title: "Verify: Device registry authenticates humidity values"
status: Draft
priority: High
owner: A. Hassan
former-id: TC-NG6T88
parent: REQ-8351896
order: b1R
links:
  - type: verifies
    target: REQ-901RZ6N
    confirmed: 75d4ba20cb76
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Detect the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
