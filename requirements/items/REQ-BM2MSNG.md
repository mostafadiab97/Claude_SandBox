---
id: REQ-BM2MSNG
type: test-case
title: "Verify: Battery backup measures the room temperature"
status: Approved
priority: High
owner: M. Farouk
tags:
  - i18n
  - connectivity
former-id: TC-ZG88ZB
parent: REQ-F9Z1FYS
order: b0B
links:
  - type: verifies
    target: REQ-W8CZJZ7
    confirmed: f070e450174f
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Detect firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
