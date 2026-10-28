---
id: REQ-ZZFZQZ0
type: test-case
title: "Verify: Home dashboard authenticates error conditions"
status: Draft
priority: High
tags:
  - security
former-id: TC-5TTMCB
parent: REQ-WR5ZJN9
order: b0W
links:
  - type: verifies
    target: REQ-3SYSXK0
    confirmed: 5e111d233bc7
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Detect the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
