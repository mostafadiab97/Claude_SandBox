---
id: REQ-PY9BHQT
type: test-case
title: "Verify: Watchdog restores humidity values"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - ux
  - release-1.0
former-id: TC-78JFCD
parent: REQ-K6FGAY0
order: b0a
links:
  - type: verifies
    target: REQ-7ENS3YJ
    confirmed: ab26978cce76
  - type: verifies
    target: REQ-0ZGTJW4
    confirmed: 97699e3cfebd
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Detect sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
