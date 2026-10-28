---
id: REQ-FXXTZX4
type: test-case
title: "Verify: Main PCB displays schedule entries"
status: Review
priority: Medium
former-id: TC-V6HV2C
parent: REQ-F9Z1FYS
order: an
links:
  - type: verifies
    target: REQ-4BYNG6Z
    confirmed: fe331aa72f1d
  - type: verifies
    target: REQ-1PHK646
    confirmed: 676ecf1ac386
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Measure relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
