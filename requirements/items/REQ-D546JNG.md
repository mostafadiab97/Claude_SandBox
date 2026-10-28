---
id: REQ-D546JNG
type: test-case
title: "Verify: Power supply limits error conditions"
status: Review
priority: High
owner: A. Hassan
former-id: TC-B0FFGH
parent: REQ-F9Z1FYS
order: b0h
links:
  - type: verifies
    target: REQ-YED15DF
    confirmed: eaf4dadef412
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
