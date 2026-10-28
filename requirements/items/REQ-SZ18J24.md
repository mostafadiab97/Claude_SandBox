---
id: REQ-SZ18J24
type: test-case
title: "Verify: Battery backup calibrates the operating mode"
status: Draft
priority: High
owner: K. Tanaka
tags:
  - release-2.0
former-id: TC-2JT1HY
parent: REQ-F9Z1FYS
order: b0R
links:
  - type: verifies
    target: REQ-QMV6ZXP
    confirmed: 872381f1db9b
  - type: verifies
    target: REQ-WVXXQG5
    confirmed: 3987fa5a3edb
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
