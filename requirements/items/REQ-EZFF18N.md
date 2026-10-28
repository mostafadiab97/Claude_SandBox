---
id: REQ-EZFF18N
type: test-case
title: "Verify: Device registry validates the room temperature"
status: Draft
priority: Medium
owner: N. Kamal
former-id: TC-V7R5HX
parent: REQ-8351896
order: b07
links:
  - type: verifies
    target: REQ-H2YF6W3
    confirmed: 051320b022ae
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Detect the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
