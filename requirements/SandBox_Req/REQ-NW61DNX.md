---
id: REQ-NW61DNX
type: test-case
title: "Verify: Telemetry pipeline authenticates energy consumption"
status: Approved
owner: A. Hassan
tags:
  - safety
  - connectivity
former-id: TC-SF6N2K
parent: REQ-8351896
order: b1f
links:
  - type: verifies
    target: REQ-XWK1AAE
    confirmed: 1e529db5157b
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Authenticate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
