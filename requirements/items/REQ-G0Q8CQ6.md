---
id: TC-1GXVKX
type: test-case
title: "Verify: Device registry reports sensor readings"
status: Draft
priority: Low
owner: A. Hassan
parent: INFO-7P4D8D
order: 30
links:
  - type: verifies
    target: SYS-RCK4NZ
    confirmed: 32fb1eff344d
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Store the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
