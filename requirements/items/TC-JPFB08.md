---
id: TC-JPFB08
type: test-case
title: "Verify: Mobile app switchs the connection state"
status: Obsolete
priority: High
owner: R. Nabil
tags:
  - regulatory
  - i18n
parent: INFO-J0FETE
order: 420
links:
  - type: verifies
    target: SYS-5GVCBE
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
