---
id: TC-DSMCJ9
type: test-case
title: "Verify: OTA server validates relay events"
status: Obsolete
priority: High
owner: Y. Saber
parent: INFO-7P4D8D
order: 1350
links:
  - type: verifies
    target: SYS-9BKWE6
    confirmed: 69aa4344ccec
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
