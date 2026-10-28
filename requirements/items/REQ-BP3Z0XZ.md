---
id: REQ-BP3Z0XZ
type: test-case
title: "Verify: OTA server synchronises firmware images"
status: Draft
priority: Medium
former-id: TC-6ZVHJM
parent: REQ-8351896
order: b0n
links:
  - type: verifies
    target: REQ-Y74G30P
    confirmed: 29497feac15d
  - type: verifies
    target: REQ-D6V3KHV
    confirmed: cc248766ef79
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Synchronise humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
