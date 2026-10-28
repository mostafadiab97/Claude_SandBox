---
id: REQ-YT5MCPX
type: test-case
title: "Verify: OTA server validates relay events"
status: Obsolete
priority: High
owner: Y. Saber
former-id: TC-DSMCJ9
parent: REQ-8351896
order: b1A
links:
  - type: verifies
    target: REQ-2ERK7CD
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
