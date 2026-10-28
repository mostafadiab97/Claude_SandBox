---
id: REQ-HC454XQ
type: test-case
title: "Verify: Backlight notifys audit records"
status: Approved
priority: Medium
owner: R. Nabil
former-id: TC-HHX223
parent: REQ-Y9VHHKA
order: aw
links:
  - type: verifies
    target: REQ-8MD3CMA
    confirmed: a04194db67ef
  - type: verifies
    target: REQ-EKMKFZ6
    confirmed: d8fdea0c8e00
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Detect safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
