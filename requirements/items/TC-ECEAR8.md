---
id: TC-ECEAR8
type: test-case
title: "Verify: Notification service displays the operating mode"
status: Approved
priority: Medium
owner: J. Müller
tags:
  - customer-request
  - accessibility
parent: INFO-J0FETE
order: 860
links:
  - type: verifies
    target: SYS-VA9RN1
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Authenticate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
