---
id: TC-XBT5PT
type: test-case
title: "Verify: Notification service synchronises firmware images"
status: Draft
priority: Low
owner: S. Adel
parent: INFO-J0FETE
order: 380
links:
  - type: verifies
    target: SYS-9WHVE0
    confirmed: b19b26310755
  - type: verifies
    target: SW-KBEPSC
    confirmed: be1f80f82e4f
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Encrypt the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
