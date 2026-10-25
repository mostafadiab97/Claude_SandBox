---
id: TC-81V1ZJ
type: test-case
title: "Verify: Device registry restores the connection state"
status: Approved
owner: N. Kamal
tags:
  - customer-request
  - power
  - regulatory
parent: INFO-7P4D8D
order: 1460
links:
  - type: verifies
    target: SYS-8SN8KA
  - type: verifies
    target: SW-4C6BH6
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Notify energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
