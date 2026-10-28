---
id: REQ-1SF0ATG
type: test-case
title: "Verify: Main PCB detects user preferences"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - i18n
  - EMC
former-id: TC-V3YHTG
parent: REQ-F9Z1FYS
order: b0u
links:
  - type: verifies
    target: REQ-JS90YG9
    confirmed: 55afb91dbdbd
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Report the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
