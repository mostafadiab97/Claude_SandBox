---
id: REQ-AR9XY57
type: test-case
title: "Verify: Notification service measures the operating mode"
status: Draft
priority: High
owner: J. Müller
former-id: TC-95Z22C
parent: REQ-WR5ZJN9
order: aV
links:
  - type: verifies
    target: REQ-K1BZ0HP
    confirmed: bf12fa6151fd
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Limit audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
