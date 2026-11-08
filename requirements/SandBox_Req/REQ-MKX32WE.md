---
id: REQ-MKX32WE
type: test-case
title: "Verify: Telemetry pipeline limits access tokens"
status: Approved
priority: High
owner: S. Adel
tags:
  - EMC
  - power
  - regulatory
former-id: TC-H9DZYA
parent: REQ-8351896
order: b0q
links:
  - type: verifies
    target: REQ-FJMWQFX
    confirmed: 35daf5402be7
  - type: verifies
    target: REQ-BWS0YBS
    confirmed: a241069de6f9
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Limit access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
