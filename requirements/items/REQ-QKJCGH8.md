---
id: REQ-QKJCGH8
type: test-case
title: "Verify: OTA server calibrates the room temperature"
status: Approved
priority: Medium
former-id: TC-5V70HD
parent: REQ-8351896
order: b0F
links:
  - type: verifies
    target: REQ-XJ2KRZB
    confirmed: af8070b2a3c3
  - type: verifies
    target: REQ-71X6D8D
    confirmed: d99755f8771b
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Detect user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
